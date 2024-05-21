Sure, here's the updated README with the project link section included:

# Excel Data Analysis Project

## Project Overview

This project involves analyzing a customer dataset, product table, fact table, and market table using Excel. The data has been preprocessed extensively in Power Query to ensure accuracy and consistency. The main objective is to generate insights through pivot tables that help in understanding sales trends, performance against targets, and profitability.

## Data Description

1. **Customer Table**
   - **customer_code**: Unique identifier for each customer.
   - **customer**: Customer name.
   - **market**: Market to which the customer belongs.
   - **platform**: Platform used by the customer.
   - **channel**: Sales channel for the customer.

2. **Product Table**
   - **product_code**: Unique identifier for each product.
   - **division**: Division of the product.
   - **segment**: Segment of the product.
   - **category**: Category of the product.
   - **product**: Product name.
   - **variant**: Variant of the product.

3. **Fact Table**
   - **date**: Date of the transaction.
   - **product_code**: Product identifier.
   - **customer_code**: Customer identifier.
   - **Qty**: Quantity sold.
   - **net_sales_amount**: Net sales amount.
   - **freight_cost**: Freight cost.
   - **manufacturing_cost**: Manufacturing cost.

4. **Market Table**
   - **market**: Market name.
   - **sub_zone**: Sub-zone of the market.
   - **region**: Region of the market.

## Pivot Tables

### 1. Yearly Revenue Analysis
   - **Description**: This pivot table shows the revenue generated each year from 2019 to 2021, along with a comparison between 2020 and 2021.
   - **Columns**: Customer, 2019, 2020, 2021, 20 v 21.
   - **Filters**: Region, Division, Market.
   - **Objective**: To analyze yearly revenue trends and identify growth or decline in sales across different regions, divisions, and markets.

### 2. Target Comparison
   - **Description**: This pivot table compares actual sales for the years 2019, 2020, and 2021 against the targets set for 2021, showing the difference and percentage achievement.
   - **Columns**: 2019, 2020, 2021, 2021 - Target, %.
   - **Filters**: Region, Division.
   - **Objective**: To evaluate sales performance against targets and identify areas needing improvement.

### 3. Profit and Loss Analysis
   - **Description**: This pivot table provides a detailed profit and loss statement for the years 2019, 2020, and 2021, with a year-over-year comparison between 2020 and 2021.
   - **Columns**: Values, 2019, 2020, 2021, 20 vs 21.
   - **Filters**: Region, Division, Market.
   - **Objective**: To analyze the profitability of different segments and markets, helping to understand cost structures and profit margins.

## Data Preprocessing

The following preprocessing steps were performed using Power Query:
- Removal of null values to ensure data completeness.
- Textual preprocessing to standardize text formats.
- Conversion of dates to the proper format.
- Transformation of normal dates to financial years for consistent reporting periods.

## Project Link

You can access the project file using the link below. Please note that the password is required to access the file.

[Project Link](https://arizonastateu-my.sharepoint.com/:x:/g/personal/ppate165_sundevils_asu_edu/ESmHu2Tlz51AlojQjgJt9CcBugXOjWmeHil4ZzOaZv-Gmw?e=TEz6Wr)

**Password**: data123

## Real-World Application

This analysis aids businesses in several ways:
- **Optimization of Sales Strategies**: By understanding sales trends and comparing performance against targets, businesses can optimize their sales strategies to focus on high-growth areas.
- **Improved Decision-Making**: Detailed profit and loss analysis helps in making informed decisions about cost management and pricing strategies.
- **Market and Segment Insights**: Analyzing data across different markets and segments enables businesses to identify profitable segments and allocate resources more effectively.

This project provides a comprehensive view of the business performance, helping stakeholders to drive growth and improve efficiency.
