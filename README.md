# Retail Sales & Inventory Analysis using Excel

## Project Overview

This project focuses on analyzing retail sales performance and inventory status using Microsoft Excel.

The objective is to understand product category performance, regional sales patterns, monthly sales trends, and inventory distribution through PivotTables, PivotCharts, calculated fields, and an interactive dashboard.

## Business Problem

Retail businesses need to monitor sales performance and inventory levels to understand product demand and identify potential stock shortages.

Analyzing sales and inventory data helps businesses monitor key performance indicators, compare regional performance, and understand inventory distribution.

This project uses Excel-based analysis and visualization to present retail business performance.

## Dataset

**Dataset Name:** Retail Store Inventory Forecasting Dataset

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/anirudhchauhan/retail-store-inventory-forecasting-dataset

The dataset includes information about:

- Date
- Store ID
- Product ID
- Category
- Region
- Inventory
- Units Sold
- Units Ordered
- Demand Forecast
- Price
- Discount
- Weather Condition
- Holiday/Promotion
- Competitor Pricing
- Seasonality

## Tools & Technologies

- Microsoft Excel
- Excel Tables
- Formulas and Calculated Columns
- PivotTables
- PivotCharts
- KPI Cards
- Dashboard Visualization

## Objectives

- Analyze total units sold.
- Compare sales volume across product categories.
- Analyze regional sales performance.
- Understand monthly sales trends.
- Calculate gross sales, discount amount, and net sales.
- Estimate profit using an explicitly assumed cost percentage.
- Analyze low, medium, and high inventory status.

## Data Analysis & Calculations

The following calculated columns were created:

| Metric | Calculation |
|---|---|
| Gross Sales | Units Sold × Price |
| Discount Amount | Gross Sales × Discount Percentage |
| Net Sales | Gross Sales − Discount Amount |
| Estimated Profit | Net Sales − Assumed Product Cost |
| Profit Margin | Estimated Profit ÷ Net Sales |
| Stock Status | Classification based on inventory level |

**Important:** Estimated Profit is an assumption-based calculation because the original dataset does not provide actual product costs. It should not be interpreted as actual business profit.

## Dashboard Features

The Excel dashboard includes four KPI cards:

- Total Units Sold
- Total Net Sales
- Total Estimated Profit
- Total Products

### Dashboard Visualizations

1. Units Sold by Product Category
2. Units Sold by Region
3. Monthly Units Sold Trend
4. Inventory Status Distribution

## Project Workflow

1. Dataset Collection – Downloaded the retail inventory forecasting dataset from Kaggle.
2. Data Preparation – Organized the dataset in Excel.
3. Excel Table Creation – Converted the data into a structured Excel table.
4. Calculated Columns – Created sales, discount, estimated profit, profit margin, and stock status calculations.
5. PivotTable Analysis – Summarized sales and inventory information.
6. PivotChart Development – Created charts for category, region, monthly trends, and inventory status.
7. Dashboard Development – Combined KPI cards and charts into a single dashboard.

## Project Structure

```text
Retail-Sales-Inventory-Analysis/
│
├── README.md
│
├── Dataset/
│   └── retail_store_inventory.csv
│
├── Excel/
│   └── Retail_Sales_Inventory_Analysis.xlsx
│
└── Images/
    └── retail_dashboard.png
```

## Key Learnings

- Practical use of Excel formulas.
- Creating and managing structured Excel tables.
- Performing business analysis using PivotTables.
- Building PivotCharts and KPI cards.
- Understanding retail sales and inventory metrics.
- Designing a business-focused Excel dashboard.

## Conclusion

This project demonstrates the use of Microsoft Excel for retail sales and inventory analysis. It transforms retail transaction and inventory data into meaningful summaries and dashboard visualizations that support business performance monitoring.
