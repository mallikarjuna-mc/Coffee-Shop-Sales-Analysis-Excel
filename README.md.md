# Coffee Shop Sales Performance Analysis

## Project Overview

This project analyzes coffee shop transaction data to understand sales performance across products, categories, store locations, months, weekdays/weekends, and business hours.

The objective is to identify key sales trends, major revenue drivers, store performance patterns, and peak business periods to support better operational and sales decisions.

## Tools Used

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Slicers
- Excel Dashboard Design

## Dataset Overview

- Original Rows: 149,117
- Cleaned Rows: 149,116
- Original Columns: 11
- Duplicate Records Removed: 1

The dataset contains transaction-level information including transaction date, transaction time, quantity sold, store location, product information, and unit price.

## Data Cleaning and Preparation

The following steps were performed using Power Query:

- Checked all columns for blank and null values.
- Removed one exact duplicate record.
- Corrected the Transaction Time data type.
- Corrected date interpretation for accurate day analysis.
- Checked quantity and unit price fields for zero and negative values.
- Created Total Sales using Transaction Quantity × Unit Price.
- Created Month Name and Month Number columns.
- Created Day Number and Day Type columns.
- Classified transactions into Weekday and Weekend.
- Extracted Hour from Transaction Time for peak-hour analysis.

## Key KPIs

- Total Sales: $698.8K
- Total Transactions: 149,116
- Total Quantity Sold: 214,470

## Business Questions

1. Which product types generate the highest and lowest sales?
2. Which product categories contribute the most and least to total sales?
3. How does sales performance change month over month?
4. How do sales differ between weekdays and weekends?
5. How does sales performance vary across store locations?
6. During which hours does the business experience peak and low sales activity?

## Key Insights

- Barista Espresso is the highest revenue-generating product type with $91.4K in sales.
- Coffee is the leading category with $270.0K in sales, followed by Tea with $196.4K.
- Coffee and Tea together contribute approximately 66.7% of total sales.
- Sales declined by 6.8% in February, followed by four consecutive months of positive growth.
- May recorded the strongest month-over-month growth at 31.8%.
- Weekdays contribute 72.06% of total sales, while weekends contribute 27.94%.
- Hell's Kitchen generated the highest store sales at $236.5K, although performance across the three stores was relatively balanced.
- The strongest sales period is between 8 AM and 10 AM, with peak sales occurring at 10 AM.

## Business Recommendations

- Ensure sufficient staffing and product availability before the 8 AM–10 AM morning peak.
- Prioritize inventory planning for Coffee and Tea while exploring opportunities to grow weaker categories.
- Use high-performing products such as Barista Espresso and Brewed Chai Tea in cross-selling and bundle experiments.
- Investigate the February sales decline before making assumptions about its cause.
- Analyze product mix and average transaction value by store before applying the same strategy across all locations.
- Compare average sales per operating day before making staffing decisions based only on weekday and weekend total sales.

## Dashboard

The interactive Excel dashboard includes:

- KPI cards
- Product type analysis
- Product category analysis
- Monthly sales growth analysis
- Store location analysis
- Hourly sales trend analysis
- Weekday vs Weekend sales share
- Interactive slicers for Month, Store Location, and Product Category

## Project Files

- `Coffee_Shop_Sales_Analysis.xlsx` — Complete Excel analysis and interactive dashboard
- `Coffee_Shop_Dashboard.png` — Dashboard preview image

## Author

Mallikarjuna M.C