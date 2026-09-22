# Pharmacy Sales Dashboard (2014–2019)

An Excel dashboard analyzing 2,108 days of pharmacy sales data across 8 drug categories.

![Dashboard Preview](dashboard_screenshot.png)

## Business Problem
A pharmacy chain needed visibility into sales performance across drug categories and time periods to inform inventory and staffing decisions.

## Dataset
- Source: Pharmacy Sales Dataset (Kaggle)
- Size: 2,108 rows × 13 columns
- Time Period: January 2014 – October 2019
- Fields: Date, 8 ATC drug categories (daily units sold), Year, Month, Hour, Weekday

## Tools and Techniques
- Microsoft Excel — PivotTables, SUM formulas, calculated columns
- Data Cleaning — Text-to-Columns for date standardization, blank-cell handling
- Visualization — Clustered bar, column, and line charts
- Dashboard Design — 2x2 layout, unified color scheme

## Key Insights

1. Paracetamol dominates sales. N02BE accounts for roughly 62% of total sales (63,005 of 127,595 units), which signals a significant concentration risk for the business.

2. 2016 was the peak year with 25,234 units sold. Sales dropped 23% in 2017 before recovering in 2018.

3. Weekend demand is the highest. Saturday (19,767 units) and Sunday (18,401 units) outsell weekdays consistently.

4. Winter seasonality is visible. January is the peak month with over 13,000 units, while July is the lowest.

## Analytical Notes
- Identified and documented a minor reconciliation difference of 3.67 units (0.003%) traced to blank cells in the source data. Assessed as non-material to the overall conclusions.
- 2019 data covers only January to October, which explains the lower annual total.

## How to Use
1. Open Pharmacy_Dashboard.xlsx
2. Navigate to the Dashboard sheet for the visual overview
3. PivotTable sheets (PT_Sales, PT_Year, PT_Weekday, PT_Month) contain source analysis

## Author
Khushi Nirwan
GitHub: https://github.com/khushinirwan
