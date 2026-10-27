# Adidas_sales_Power-BI-Dashboard
Interactive Power BI dashboard analysing Adidas sales by month, state, region, product and retailer.
 Objective
To turn raw sales data into a simple dashboard that shows sales, profit and trends at a glance, and helps answer: which months, products and retailers drive the most sales?

## Dataset
Public Adidas US sales dataset (add the source link here, e.g., Kaggle). Fields include retailer, region, state, product, units sold, price, total sales and operating profit.

## Tools Used
- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures)
- Excel

## What I Did
1. Cleaned and prepared the data in Power Query (fixed data types, removed errors and blanks).
2. Created DAX measures for Total Sales, Total Profit, Units Sold, Average Price and Profit Margin.
3. Built 5 visuals: monthly sales trend, state-wise map, region-wise donut, product-wise bar chart and retailer-wise bar chart.
4. Added slicers for year, sales channel and month, plus a reset button.

## Key Numbers
| Metric | Value |
|---|---|
| Total Sales | 135.80M |
| Total Profit | 52.81M |
| Units Sold | 3M |
| Average Price | 40.36 |
| Profit Margin | 43.53% |

## Key Insights
- Sales peak in July (18.9M) and December (16.8M) and are lowest in April (5.1M), which shows a seasonal pattern.
- Men's Street Footwear is the top-selling product.
- West Gear and Foot Locker are the top retailers by sales.

## Files in this Repository
- `Adidas_Sales_Dashboard.pbix` - Power BI file
- `Adidas_Sales_Dashboard.pdf` - PDF export of the dashboard
- `Adidas_Dashboard.png` - dashboard screenshot

## What I Learned
Data cleaning with Power Query, writing basic DAX measures, choosing the right chart for each question, and checking visuals against KPI totals.
