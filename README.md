# Retail-Sales-Analysis-SQL-Project
Retail sales analysis using PostgreSQL to clean transaction data, analyze category-wise revenue, explore customer purchasing patterns, identify top customers, and examine monthly sales and time-of-day trends.
# Retail Sales Analysis using SQL

## Project Overview

This project analyzes retail sales transaction data using SQL to identify sales trends, understand customer purchasing behavior, and evaluate product category performance. It demonstrates how SQL can be used to clean data, perform exploratory analysis, and answer business questions using structured datasets.

## Objectives

* Clean and prepare retail sales data for analysis.
* Analyze sales performance across product categories.
* Identify high-value customers and purchasing patterns.
* Explore monthly sales trends and peak sales periods.
* Use SQL queries to generate insights that support business decision-making.

## Tools and Technologies

* **Database:** PostgreSQL
* **Language:** SQL
* **Dataset:** Retail sales transaction data
* **Techniques:** Data cleaning, exploratory data analysis, aggregation, filtering, joins where applicable, Common Table Expressions (CTEs), window functions, and ranking.

## Dataset

The dataset contains retail transaction information, including:

* `transaction_id` — Unique identifier for each transaction
* `sale_date` — Date of the sale
* `sale_time` — Time of the sale
* `customer_id` — Customer identifier
* `gender` — Customer gender
* `age` — Customer age
* `category` — Product category
* `quantity` — Number of units purchased
* `price_per_unit` — Price per unit
* `cogs` — Cost of goods sold
* `total_sale` — Total transaction value

## Project Workflow

### 1. Database Setup

Created a PostgreSQL database and prepared a table to store the retail transaction data.

### 2. Data Cleaning

* Checked for missing and null values.
* Identified records requiring data-quality checks.
* Prepared the dataset for analysis.

### 3. Exploratory Data Analysis

Used SQL queries to explore the dataset and understand sales patterns, customer behavior, and category performance.

### 4. Business Questions

The analysis addresses questions such as:

1. What are the total sales and number of transactions?
2. Which product categories generate the most revenue?
3. Which customers contribute the highest sales?
4. What are the sales trends across different months?
5. Which transactions involve larger purchase quantities?
6. How does sales performance vary by gender?
7. What are the peak sales periods by time of day?
8. Which product categories have the highest transaction counts?
9. How do customer purchasing patterns differ?
10. Which categories and customers should be examined for further business opportunities?

## Key Skills Demonstrated

* SQL data cleaning and validation
* PostgreSQL database operations
* Aggregation using `SUM()`, `COUNT()`, and `AVG()`
* Filtering and grouping using `WHERE` and `GROUP BY`
* Date and time analysis
* Common Table Expressions (CTEs)
* Window functions and ranking
* Translating business questions into SQL queries

## Repository Structure

```text
Retail-Sales-Analysis-SQL/
├── README.md
├── retail_sales.csv
└── retail_sales_analysis.sql
```

## How to Run the Project

1. Install PostgreSQL and open a SQL client such as pgAdmin.
2. Create the database using the SQL script.
3. Create the retail sales table.
4. Import `retail_sales.csv` into the table, ensuring the CSV column headers match the table schema.
5. Execute the data-cleaning and analysis queries in `retail_sales_analysis.sql`.
6. Review the query outputs to identify sales trends and customer purchasing patterns.

**Note:** Run the queries in the order provided in the SQL script and verify that the CSV has been imported successfully before executing the analysis.

## Business Value

This project demonstrates how structured sales data can be analyzed to understand revenue patterns, evaluate product categories, identify valuable customer segments, and support data-driven retail decisions.

## Conclusion

The project showcases practical SQL and PostgreSQL skills through retail data preparation, exploratory analysis, and business-focused querying. It provides a foundation for further analysis using visualization tools such as Power BI.

---

*This project is intended for educational and portfolio purposes.*
