# Datheon_Data_Analytics_-_Power_BI_Internship
# Superstore Sales Dashboard (Power BI)

Executive sales dashboard built for the Datheon Data Analytics & Power BI Internship.

## Overview
An interactive Power BI dashboard that turns raw Superstore sales records into KPI scorecards, a monthly sales trend, and a category/sub-category breakdown.

## Data Model
Star schema built in Power Query:
- Fact Orders: Order ID, Order Date, Customer ID, Product ID, Region, Sales, Quantity, Discount, Profit
- Dim Customer: Customer ID, Customer Name, Segment
- Dim Product: Product ID, Product Name, Category, Sub-Category
- Dim Date: Date, Year, Month Number, Month Name, Quarter

All relationships are many-to-one with single-direction filtering.

## DAX Measures
- Total Sales
- Total Profit
- Total Orders
- Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
- YoY Sales Growth %

## Visuals
- KPI cards: Sales, Profit, Orders, Profit Margin
- Monthly sales line chart
- Category and sub-category treemap
- Year and Region slicers

## Files
- Superstore_Dashboard.pbix: Power BI report
- Superstore_Dashboard.pdf: exported executive report
- README.md

## Tools
Power BI Desktop, Power Query, DAX

## Author
Oche Oyifie
