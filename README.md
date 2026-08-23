
Then add the other measures we created: Gross Profit, Gross Margin %, Total Customers, Return Rate %, Previous Year Revenue and YoY Growth.

---

# 6. README should be the main presentation

Your README should contain approximately:

```markdown
# FoodMart Power BI Data Analytics Assessment

An end-to-end retail analytics project developed using Microsoft Power BI.

## Project Overview

The project analyses FoodMart retail transaction data from 1997–1998 to identify sales trends, customer behaviour, product performance, profitability, returns, and regional performance.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Dimensional Modelling
- Star Schema
- Data Visualization

## Data Model

The solution uses:

- Fact_Transactions
- Fact_Returns
- Dim_Customer
- Dim_Product
- Dim_Store
- Dim_Calendar

## Key KPIs

- Total Revenue: $1.76M
- Gross Profit: $1.05M
- Gross Margin: 59.67%
- Quantity Sold: 833K
- Purchasing Customers: 8,842
- Return Rate: 0.99%
- High Priority Revenue: $141.63K

## Dashboard Pages

### Executive Sales Overview

![Executive Dashboard](screenshots/executive_sales_overview.png)

### Product Performance Analysis

![Product Performance](screenshots/product_performance.png)

### Customer Analysis

![Customer Analysis](screenshots/customer_analysis.png)

## Key Business Insights

1. Revenue increased significantly from 1997 to 1998.
2. USA contributes approximately 66.8% of total revenue.
3. North West is the strongest-performing sales region.
4. Customer revenue is concentrated in specific membership and income segments.
5. Overall product return rate is low, but several products show comparatively high return quantities.

## Business Recommendations

1. Expand sales initiatives in Mexico and Canada to reduce reliance on the USA market.
2. Use customer segmentation for targeted loyalty, retention, and upselling campaigns.
3. Monitor low-performing and high-return products and investigate product quality, pricing and placement.

## Important Note

The source dataset was provided for an assessment and is therefore not included in this repository.
