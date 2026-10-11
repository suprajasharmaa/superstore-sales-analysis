# Superstore Sales & Profitability Analysis

📄 [Case Study Report](./Superstore_Sales_Analysis_Portfolio.docx) | 📊 [Excel Workbook](./Superstore_Sales_Analysis_Workbook.xlsx)

## Overview
This project analyses profitability across a Superstore retail dataset of 9,994 orders (2014-2017). The goal was to identify which categories, regions, and discount behaviors drive or drain profit, and to forecast future sales using historical trends.

## Dataset
- **Source:** Kaggle - Superstore Sales dataset
- **Size:** 9,994 rows × 21 columns
- **Time period:** January 2014 - December 2017
- **Key columns:** Order Date, Sales, Profit, Discount, Quantity, Region, Category

## Tools Used
Microsoft Excel - PivotTables & PivotCharts, Data Analysis ToolPak (correlation & regression), Power Pivot (Data Model, DAX measures), Forecast Sheet (exponential smoothing)

## Key Findings
- Discounts above 20% generate an average loss of $107 per order - no-discount orders are the only consistently profitable tier
- Sales explains about 23% of the variation in Profit (R² = 0.23, statistically significant, Sales coefficient 0.18) - confirmed via regression, not just correlation
- Technology drives 50.79% of total profit despite Furniture taking up a full third of the product catalogue but contributing only 6.44%
- The South region generates the highest revenue per order ($242) despite the lowest order volume
- The 12-month sales forecast projects continued seasonal growth, with autumn (Sep-Nov) consistently the strongest period

## Recommendations
- Cap discounts at 20% across all regions and categories
- Investigate and restructure the underperforming Furniture category
- Study the South region's higher-value sales approach for replication elsewhere
- Align inventory and staffing planning to the forecasted autumn demand peak

## Files in This Repository
- `Superstore_Sales_Analysis_Workbook.xlsx` - full workbook: cleaned data, dashboard, Power Pivot model, DAX measures, forecast
- `Superstore_Sales_Analysis_Portfolio.docx` - case study write-up (problem, method, insights, recommendations)
- `README.md` - this file

## How to Run
1. Download the dataset from Kaggle (Superstore Sales dataset)
2. Open the workbook - the Dashboard tab opens first with the full visual summary
3. Supporting sheets follow in this order: RAW Data → Clean Data → Pivots → Regression → Sales Forecast → Analysis → Measure Validation, for anyone who wants to see the underlying method

