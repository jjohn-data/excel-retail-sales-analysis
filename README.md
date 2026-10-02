# Excel Retail Sales Analysis

**Skills:** Excel | PivotTables | Power Pivot | DAX | Dashboard Design | Business Analysis

## Project Overview

This project analyzes transactional online-retail data in Microsoft Excel with a focus on revenue, geographic concentration, seasonality, and product return risk.

The dashboard uses the **2009–2010** portion of the Online Retail II data and is designed as an executive-style business analysis rather than a purely technical exercise.

## Dataset

The source is the **Online Retail II** dataset from the UCI Machine Learning Repository.

- Source: UCI Machine Learning Repository
- Dataset: Online Retail II
- DOI: https://doi.org/10.24432/C5CG6D
- License: CC BY 4.0
- Original coverage: December 2009 to December 2011
- Analysis focus in this project: 2009–2010

The source data represents transactions from a UK-based non-store online retailer. UCI documents fields such as invoice number, product code and description, quantity, invoice date, unit price, customer ID, and country.

## Business Questions

1. Which products generate the highest revenue?
2. Which countries contribute most to revenue?
3. How does revenue change over time?
4. Which products combine high activity with unusually high return rates?

## Analytical Approach

The workbook uses Excel-based analysis tools to transform transaction data into business-facing summaries:

- PivotTables for aggregation and exploration
- Power Pivot / DAX for measures and model-driven calculations
- dashboard charts for revenue, geography, time trends, and return risk
- explicit review of incomplete-period effects in December 2010

## Dashboard Preview

![Dashboard Screenshot](dashboard/dashboard_screenshot.png)

The dashboard contains:

- Top 10 Products by Revenue
- Top 10 Countries by Revenue
- Monthly Revenue Trend
- Top 10 High-Return Products
- summary business insights

## Key Findings

- The United Kingdom accounts for the dominant share of revenue in the analyzed period.
- Revenue increases strongly in the later months of 2010.
- Several high-volume products also appear among products with high return rates.
- December 2010 is visibly lower than November and is marked as potentially incomplete in the dashboard.

These are descriptive findings from the workbook. In particular, the Q4 pattern should not automatically be interpreted as proof of seasonality without comparing complete periods across multiple years.

## Business Interpretation

Potential business actions suggested by the analysis include:

- review high-return products for product-quality, fulfillment, or expectation issues,
- incorporate late-year demand increases into inventory planning,
- monitor dependence on the UK market,
- track return-rate KPIs alongside revenue rather than evaluating products only by sales.

These are analytical recommendations for further investigation, not causal conclusions.

## Included Files

```text
excel-retail-sales-analysis/
├── dashboard/
│   ├── dashboard_screenshot.png
│   └── sales_dashboard_report.pdf
├── data/
│   └── online_retail_sales_analysis.xlsx
├── .gitignore
└── README.md
```

## How to Review the Project

Without Excel, use:

- `dashboard/dashboard_screenshot.png`
- `dashboard/sales_dashboard_report.pdf`

For the full analysis, open:

```text
data/online_retail_sales_analysis.xlsx
```

in Microsoft Excel with support for PivotTables and the Data Model / Power Pivot features used by the workbook.

## Limitations

- The dashboard focuses on the 2009–2010 period rather than the full two-year source dataset.
- The final month shown may be incomplete and should not be compared directly with complete months without checking coverage.
- Return-rate analysis depends on how returns/cancellations are encoded and calculated in the workbook.
- Revenue concentration does not by itself explain customer behavior or market potential.
- The analysis is descriptive and does not establish causal relationships.

## Portfolio Role

This repository is the primary Excel-focused project in the portfolio. It demonstrates spreadsheet-based business analysis, PivotTables, Power Pivot/DAX, KPI interpretation, and executive dashboard communication.
