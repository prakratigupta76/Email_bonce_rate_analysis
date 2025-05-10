# 📧 Email Bounce Rate Analysis
---

## Objective

A client reported an unusual increase in their email campaign bounce rate in **May**. The objective of this assignment is to:

- Investigate the root cause of the spike.
- Support the findings with **data-backed evidence**.
- Propose actionable **next steps** or a resolution plan.

---

## Files Included

| File Name                          | Description                                         |
|-----------------------------------|-----------------------------------------------------|
| `Email Bounce Rate Analysis Report.pdf`  | Main report outlining findings, charts, and solutions. |
| `Email Bounce Rate Analysis Data.xlsx` | Cleaned Excel file with PivotTables, slicers, and transformations. |

---

## Summary of Findings

- The bounce rate in **May** increased to **0.27%**, more than double the rate from surrounding months.
- The domain **centrum.sk** accounted for **~31% of all bounces** in May.
- The most frequent bounce reason was **SMTP code 554** (permanent failure).
- These patterns suggest domain-specific blocking or sender reputation issues.

---

## Tools & Techniques Used

- **Excel**: For data transformation, pivot tables, slicers, and charts.
- **Power Query**: To unpivot and structure the dataset.
- **SMTP Code Categorization**: To distinguish success, soft bounces, and hard bounces.
- **Bounce Rate Calculation**: Total bounces / total emails sent, by month.

---

## Proposed Solutions

- **Clean email list**: Suppress invalid or high-risk addresses (especially from centrum.sk).
- **Review sender reputation**: Investigate domain reputation and spam triggers.
- **Implement email warmup**: Gradually increase send volume to build ISP trust.
- **Contact affected ISPs**: If blacklisting or filtering is suspected.

---

## Supporting Visuals

Visualizations included in the report:
- **Bounce Rate Over Time** (Feb–Aug)
- **SMTP Code Trends by Month**
- **Bounce Count by Email Domain**
- **Code vs Domain Heatmap**
