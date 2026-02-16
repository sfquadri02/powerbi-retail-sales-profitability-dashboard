# Retail Sales & Profitability Analytics Dashboard – Power BI
Interactive Power BI dashboard analyzing retail sales performance, profitability drivers, and time-based growth trends using advanced DAX and time intelligence functions.

## Project Overview
- This project presents a 3-page interactive Business Intelligence dashboard built in Power BI using the Superstore Sales Dataset (Kaggle).
- The objective is to transform raw retail transactional data into actionable business insights through advanced DAX, time intelligence, and structured storytelling.
- The dashboard is designed for executive-level reporting and analytical deep-dives into profitability and growth performance.

## Dashboard Structure - Executive Overview
Provides a high-level snapshot of overall business performance.

### Key KPIs:

- Total Sales: $2.30M
- Total Profit: $286K
- Profit Margin: 12.47%
- YoY Growth: 46.88%

### Business Insights:

- Technology is the leading revenue contributor.
- Consumer segment drives majority of total sales.
- Growth acceleration is strongest in Q4.
- Strong year-over-year performance indicates positive momentum.

<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/34949a44-0ab5-4d2d-bda2-01524f9f758f" />

## Dashboard Structure - Profit Analysis
This page performs a deep-dive into structural profitability and identifies loss-making areas.

### Key Findings:

- Profit is concentrated in Technology and Office Supplies.
- Furniture underperforms due to losses in Tables and Bookcases.
- Approximately 2K loss-making orders negatively impact margins.

### Analytical Features:

- Profit Marginn % by Sub-Category Clustered Column Chart
- Sub-category Profit Breakdown
- State-level Profit Margin % Matrix
- Conditional formatting to highlight negative zones
- Dynamic slicers for Category, Sub-Category, Segment, and Region

<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/86a254e8-286c-447b-8dae-9a0b8b34712c" />

## Time Intelligence
This page evaluates performance sustainability and trend behavior using advanced DAX time functions.

### Implemented Time-Based Measures:

- Sales LY (SAMEPERIODLASTYEAR)
- YoY Growth %
- Sales YTD (TOTALYTD)
- Sales MTD (TOTALMTD)
- Quarterly Comparisons
- Cumulative Sales Trend

### Insights:

- Strong YoY growth momentum.
- Q4 demonstrates highest quarterly performance.
- Weekday sales outperform weekend sales.
- Growth consistency supported by cumulative trend analysis.

<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/f90f13cb-c3b6-4ad1-92cb-36a566d05bff" />

## Technical Implementation
### Data Modeling
- Star schema approach
- Dedicated Date Table
- Proper relationships for time intelligence
## DAX Measures Created

Total Sales

Total Profit

Profit Margin %

Sales LY

YoY Growth %

Sales YTD

Sales MTD

Loss Orders

Average Profit per Order

Advanced Techniques

SAMEPERIODLASTYEAR

TOTALYTD

TOTALMTD

Conditional Formatting

Dynamic Slicers

Navigation Buttons

Executive Storytelling Layout
