# Amazon Power BI Dashboard Project

## Table of Contents

1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Dataset Overview](#dataset-overview)
   - [Dataset Structure](#dataset-structure)
   - [Example Rows from the Dataset](#example-rows-from-the-dataset)
   - [Dataset Insights](#dataset-insights)
4. [Data Sources](#data-sources)
5. [Technology Stack](#technology-stack)
6. [Setup Instructions](#setup-instructions)
7. [Detailed Analysis Insights](#detailed-analysis-insights)
   - [Sales Performance Analysis](#sales-performance-analysis)
   - [Profit Margins Analysis](#profit-margins-analysis)
   - [Sales by Category Analysis](#sales-by-category-analysis)
   - [Quantity Sold Analysis](#quantity-sold-analysis)
   - [Geographical Sales Analysis](#geographical-sales-analysis)
8. [Conclusion](#conclusion)
9. [Contact Information](#contact-information)

## Project Overview

The Amazon Power BI Dashboard Project is developed to provide a comprehensive and interactive analysis of the sales performance across various product categories within Amazon's ecosystem. Utilizing Microsoft Power BI, the dashboard delivers in-depth insights into total sales, profitability, quantity sold, and regional sales distributions. By visualizing and analyzing the data, the project's goal is to empower stakeholders with actionable insights, ultimately improving business strategies and performance.

## Key Features

- **Interactive Visualizations**: The dashboard comprises numerous charts and maps that allow users to drill down into specific metrics and filter data dynamically.
  
- **Comprehensive Sales Analysis**:
  - **Total Sales Metrics**: Insight into which products generate the most revenue.
  
- **Profit Analysis**:
  - Examination of profit margins to determine the most lucrative product categories.

- **Sales by Category**:
  - Breakdown of sales performance by different categories for better decision-making.

- **Quantity Sold Overview**:
  - Insights into which categories have the highest units sold, guiding inventory and marketing efforts.

- **Geographical Sales Insights**:
  - Filled maps to indicate the regions with the highest sales, aiding in regional marketing strategies.

## Dataset Overview

The dataset used in this project contains essential information about sales transactions through the following attributes:

### Dataset Structure

The dataset consists of sales records with the following columns:

1. **Row ID**: A unique identifier for each row in the dataset.
2. **Order ID**: A unique identifier for each sales transaction.
3. **Order Date**: The date on which the order was placed.
4. **Ship Date**: The date on which the order was shipped.
5. **Ship Mode**: The shipping method used for the order.
6. **Customer ID**: Unique identifier for customers.
7. **Customer Name**: Name of the customer who placed the order.
8. **Segment**: Market segment category (e.g., Consumer, Corporate).
9. **Country**: Country of the customer.
10. **City**: City of the customer.
11. **State**: State of the customer.
12. **Postal Code**: Customer's postal code.
13. **Region**: Geographic region (e.g., East, West, Central, South).
14. **Product ID**: Unique identifier for each product.
15. **Category**: General product category (e.g., Office Supplies).
16. **Sub-Category**: More detailed product classification.
17. **Product Name**: Name of the product.
18. **Sales**: Total sales revenue for the transaction.
19. **Quantity**: Number of units sold.
20. **Discount**: Discount applied to the sales price.
21. **Profit**: Profit earned from the sale.

### Example Rows from the Dataset

Here are a few example entries from the dataset to illustrate its structure:

| Row ID | Order ID       | Order Date | Ship Date   | Ship Mode       | Customer ID | Customer Name       | Segment   | Country      | City           | State      | Postal Code | Region | Product ID       | Category          | Sub-Category      | Product Name                                                 | Sales     | Quantity | Discount | Profit    |
|--------|----------------|------------|-------------|-----------------|-------------|---------------------|-----------|--------------|----------------|------------|-------------|--------|-------------------|--------------------|-------------------|-------------------------------------------------------------|-----------|----------|----------|-----------|
| 1      | CA-2016-152156 | 11/8/2016  | 11/11/2016  | Second Class     | CG-12520    | Claire Gute         | Consumer  | United States | Henderson      | Kentucky   | 42420       | South  | FUR-BO-10001798  | Furniture           | Bookcases         | Bush Somerset Collection Bookcase                          | 261.96    | 2        | 0        | 41.9136   |
| 2      | CA-2016-152156 | 11/8/2016  | 11/11/2016  | Second Class     | CG-12520    | Claire Gute         | Consumer  | United States | Henderson      | Kentucky   | 42420       | South  | FUR-CH-10000454  | Furniture           | Chairs            | Hon Deluxe Fabric Upholstered Stacking Chairs             | 731.94    | 3        | 0        | 219.582   |
| 3      | CA-2016-138688 | 6/12/2016  | 6/16/2016   | Second Class     | DV-13045    | Darrin Van Huff     | Corporate | United States | Los Angeles    | California | 90036       | West   | OFF-LA-10000240  | Office Supplies     | Labels            | Self-Adhesive Address Labels for Typewriters by Universal  | 14.62     | 2        | 0        | 6.8714    |
| 4      | US-2015-108966 | 10/11/2015 | 10/18/2015  | Standard Class   | SO-20335    | Sean O'Donnell      | Consumer  | United States | Fort Lauderdale | Florida    | 33311       | South  | FUR-TA-10000577  | Furniture           | Tables            | Bretford CR4500 Series Slim Rectangular Table              | 957.5775  | 5        | 0.45     | -383.031  |
| 5      | US-2015-118983 | 11/22/2015 | 11/26/2015  | Standard Class   | HP-14815    | Harold Pawlan       | Home Office | United States | Fort Worth     | Texas      | 76106       | Central | OFF-AP-10002311  | Office Supplies     | Appliances        | Holmes Replacement Filter for HEPA Air Cleaner              | 68.81     | 5        | 0.8      | -123.858  |

### Dataset Insights

- **Date Range**: The dataset spans several years, from 2014 to 2017, providing ample opportunity for trend analysis across seasons, quarters, and years.

- **Segment Diversity**: The dataset includes multiple customer segments (Consumer, Corporate, Home Office), allowing for segmentation analysis and targeted marketing insights.

- **Product Variety**: It covers a wide range of categories and sub-categories, providing a comprehensive view of product diversity and customer preferences.

- **Profitability Analysis**: Various products demonstrate contrasting profitability, with some yielding significant losses. This data can inform decisions regarding pricing strategies and inventory management.

- **Geographical Insights**: The dataset includes extensive geographical information, enabling analysis of regional performance differences, such as sales trends in specific states or cities.

## Data Sources

The dashboard utilizes raw data extracted from various sources to reflect an accurate picture of sales dynamics:

- **Sales Records**: Data collected from Amazon's sales transactions.
- **Product Listings**: Information regarding product specifications across categories.
- **Customer Feedback**: Data sourced from customer reviews and ratings.
- **Market Trends**: External sources providing context on industry performance metrics.

## Technology Stack

- **Microsoft Power BI**: The primary tool for creating interactive dashboards and visual analytics.
- **Data Extraction Tools**: Utilized for importing data from external sources into Power BI.
- **Database Technologies**: Such as SQL Server or CSV files that store the transactional and review data used for analysis.
- 
## Detailed Analysis Insights

### Sales Performance Analysis

- **Total Sales**: 
  - The analysis indicates that phones are the leading product category in terms of sales volume, demonstrating consumer preference for mobile technology.
  - A detailed sales trend can pinpoint peak sales periods, suggesting seasonal demands.

### Profit Margins Analysis

- **Category Profits**: 
  - The technology category yields the highest profits, suggesting premium pricing strategies. This is followed by Office Supplies and Furniture.
  - Understanding cost structures in each category can help optimize pricing and inventory management.

### Sales by Category Analysis

- **Sales Insights**: 
  - The data reveals that Technology consistently outperforms other categories in sales, indicating high consumer demand.
  - Office Supplies and Furniture follow, highlighting potential areas for marketing focus or promotional efforts.

### Quantity Sold Analysis

- **Units Sold**: 
  - Office Supplies lead the charge in quantity sold, reflecting their accessibility and everyday need.
  - Furniture and Technology follow, indicating stable demand but the need for strategic inventory management.

### Geographical Sales Analysis

- **Regional Sales Performance**: 
  - The filled map demonstrates that California has the highest sales volume, followed by Ottawa and Texas. This highlights geographical regions worth targeting for marketing and sales campaigns.
  - Understanding regional preferences can inform localized strategies for product promotions.

## Conclusion

The Amazon Power BI Dashboard Project successfully analyzes complex sales data and presents it in an interactive format, making it easier for stakeholders to derive meaningful insights. By utilizing this dashboard, businesses can identify trends, optimize product offerings, and ultimately drive growth. The dashboard serves as a powerful tool for decision-making and strategic planning, enhancing overall sales performance and profitability.
