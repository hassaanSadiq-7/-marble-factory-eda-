# Marble & Tile Industry Sales — Exploratory Data Analysis

Exploratory Data Analysis of a 5,000+ row synthetic sales dataset modeled on Pakistan's marble/tile industry, using Python (Pandas, NumPy, Matplotlib, Seaborn).

## Objective
Clean, explore, and analyze sales data to uncover business-relevant patterns — similar to what a data analyst would do for a real manufacturing/trading business.

## What Was Done
- **Data Cleaning**: Handled missing values (Discount_pct filled with 0, DeliveryDays filled with median) and removed duplicate records
- **Univariate Analysis**: Explored distribution of categorical (Category, City, MarbleType, etc.) and numeric (Quantity, Price, Revenue, etc.) columns
- **Bivariate Analysis**: Category vs Revenue, City-wise demand, Discount vs Quantity relationships
- **Correlation Analysis**: Heatmap of numeric variables
- **Time-Series Analysis**: Monthly sales trend showing seasonal demand patterns

## Key Insights
- **Quantity_sqft** has the strongest correlation (0.8) with revenue — the main driver of sales value
- **Seasonal pattern**: Peak sales occur in **October** (favorable construction weather); lowest in summer months (Jun–Aug) due to heat slowing construction activity
- **Onyx** is the most expensive category; **Tile** is the most affordable
- Discounts are given in fixed tiers (0%, 5%, 10%, 15%) rather than being tied to order size

## Tools Used
Python · Pandas
