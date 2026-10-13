# ☕ Starbucks Sales & Business Performance Analysis

An end-to-end data analytics project exploring Starbucks' overall sales performance, customer segments, and product and menu performance using **Python, PostgreSQL, and Power BI**.

The project transforms raw business data into actionable insights through exploratory data analysis, SQL-based analysis, and interactive dashboards designed to support data-driven business decisions.

## 📌 Project Overview

The objective of this project is to analyze Starbucks sales and customer purchasing patterns to understand business performance, identify valuable customer segments, evaluate product performance, and uncover opportunities for revenue growth.

The project follows a complete data analytics workflow, starting with data exploration and cleaning in Python, followed by initial business analysis in PostgreSQL, and ending with interactive Power BI dashboards.

## 🎯 Business Objectives

- Analyze overall sales performance and revenue trends.
- Identify high-value and high-volume customer segments.
- Understand customer purchasing behavior and segmentation.
- Evaluate product and menu performance.
- Identify top-performing and underperforming products.
- Examine purchasing patterns across stores, payment methods, and customer types.
- Generate actionable insights to support sales growth and business optimization.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Exploratory Data Analysis (EDA), data cleaning, and preprocessing |
| Pandas & NumPy | Data manipulation and analysis |
| Matplotlib & Seaborn | Data visualization during EDA |
| PostgreSQL | SQL queries and initial business insights |
| Power BI | Interactive dashboards and business intelligence |
| SQL | Data extraction, aggregation, filtering, and analysis |
| Git & GitHub | Project version control and documentation |

## 🔄 Project Workflow

**1. Data Exploration & Preparation — Python**

- Explored the datasets using Pandas and NumPy.
- Examined data types, missing values, duplicate records, and data consistency.
- Cleaned and prepared the sales data for further analysis.
- Used exploratory analysis to understand the structure and characteristics of the data.

**2. Initial Business Analysis — PostgreSQL**

- Imported the prepared datasets into PostgreSQL.
- Wrote SQL queries to extract initial business insights.
- Used aggregations, filtering, grouping, and joins where required.
- Analyzed sales, customer behavior, and product-related metrics.

**3. Data Extraction — SQL to Power BI**

- Used direct SQL queries to retrieve the required analytical datasets from PostgreSQL.
- Imported the query results into Power BI.
- Prepared the data for dashboard development and business reporting.

**4. Dashboard Development — Power BI**

Created three interactive dashboards to analyze different aspects of Starbucks' business performance.

## 📊 Power BI Dashboards

### 1. Sales Overview Dashboard

<img width="1308" height="727" alt="Sales overview" src="https://github.com/user-attachments/assets/b54078ea-8360-42c4-9b4e-6ac6986f2219" />



Provides a high-level view of Starbucks' overall sales performance.

**Key analytical areas:**
- Total revenue and sales performance.
- Total transactions and quantity sold.
- Sales trends over time.
- Store-level sales comparisons.
- Payment method distribution.
- Customer type and purchasing channel analysis.

**Business value:** Helps evaluate overall business performance, identify sales patterns, and understand which channels and stores contribute to revenue.

### 2. Customer Segment Analysis Dashboard


<img width="1307" height="727" alt="Customer Segment Analysis" src="https://github.com/user-attachments/assets/4a757d72-5ffb-4115-8331-d46a6bd3cffa" />


Focuses on customer demographics, segmentation, and purchasing behavior.

**Key analytical areas:**
- Customer distribution across age groups and segments.
- Highest-value customer segments based on revenue.
- Largest customer segments based on customer count.
- Customer purchasing patterns.
- Revenue contribution by customer segment.
- Comparisons of customer volume and sales contribution.

**Business value:** Helps identify valuable customer groups, understand differences between customer volume and revenue contribution, and develop targeted marketing and customer retention strategies.

### 3. Product & Menu Performance Dashboard


<img width="1305" height="727" alt="Product   Menu Performance" src="https://github.com/user-attachments/assets/b2653611-ef88-42bf-bb45-1caf86a19f10" />


Evaluates the performance of Starbucks menu items and product categories.

**Key analytical areas:**
- Best-selling products.
- Product revenue and sales volume.
- Product and menu category performance.
- Quantity sold across menu items.
- Average selling price and product comparisons.
- Nutritional attributes of menu items, where relevant to the analysis.

**Business value:** Helps identify popular and high-revenue products, evaluate menu performance, and uncover opportunities for product promotion and menu optimization.

## 📁 Dataset Description

The project uses three datasets covering sales transactions, customer information, and menu item attributes.

| Dataset | Records | Key Information |
|---|---:|---|
| `sales_cleaned.csv` | 9,936 | Transaction IDs, store IDs, timestamps, customers, menu items, quantities, prices, revenue, payment modes, and customer types |
| `customers.csv` | 500 | Customer IDs, names, contact details, age, and gender |
| `items.csv` | 77 | Menu items, calories, fat, carbohydrates, fiber, protein, item type, and item IDs |

The datasets support analysis across sales, customers, and products. The sales data connects to customer and menu information through customer and item identifiers.

## 💡 Key Business Questions

### Sales Performance
- What is the total revenue generated?
- How do sales change over time?
- Which stores contribute the most revenue?
- Which payment methods and customer types are most commonly used?
- When do sales peak?

### Customer Analysis
- Which customer segment generates the highest revenue?
- Which segment has the largest customer base?
- Does the largest customer segment also generate the most revenue?
- How do purchasing patterns vary across customer groups?
- Which customer groups offer opportunities for retention and growth?

### Product & Menu Performance
- Which menu items generate the highest revenue?
- Which products sell the highest quantities?
- Which products or categories underperform?
- How do product prices relate to sales performance?
- Which menu items could benefit from additional promotion?


## 🧠 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- SQL querying and relational data analysis
- Data extraction from PostgreSQL
- Business intelligence and dashboard development
- KPI selection and performance monitoring
- Customer segmentation and revenue analysis
- Data visualization and business storytelling
- Translating business questions into analytical insights


## 🚀 Project Outcome

This project demonstrates an end-to-end data analytics workflow using Python, PostgreSQL, and Power BI. By combining exploratory analysis, SQL-based data extraction, and interactive reporting, it provides a structured approach to understanding sales performance, customer behavior, and menu performance.

The three dashboards turn business data into an accessible visual reporting solution that supports performance monitoring, customer analysis, and product-level decision-making.

## 👨‍💻 Author

**Uday Tiwari**  
**College:** IIIT-Naya Raipur

**Project:** Starbucks Sales & Business Performance Analysis

**Tools & Technologies:** Python | PostgreSQL | SQL | Power BI


