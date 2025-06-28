# 🛒 Sales Analysis Project using PySpark & Databricks
This project focuses on analyzing customer purchase behavior using transactional sales and product menu data. The analysis was performed using **PySpark** in **Databricks**, and the final output was visualized using a Databricks dashboard.

## 📌 Project Overview
The goal is to perform key aggregations that help understand customer spending patterns and product performance.
The project includes:
- Structured data ingestion using defined schemas
- PySpark DataFrame transformations and joins
- Business aggregations (like total amount spent per customer)
- Visualization via Databricks-native dashboards

## 📂 Input Files
Both files were uploaded to **DBFS (Databricks File System)**:
- `sales.txt` — Transactional data with customer and product references at "dbfs:/FileStore/tables/project_sales_analysis/sales.txt"
- `menu.txt` — Master data for product name and price at ""dbfs:/FileStore/tables/project_sales_analysis/menu.txt

## ⚙️ Prerequisites
To execute this project, ensure the following:
- Databricks Community or Pro account
- Databricks Runtime 11.3+ (for PySpark compatibility)
- Files uploaded to the appropriate DBFS location
- Basic familiarity with PySpark and DataFrames
