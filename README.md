# 📊 Project Overview

The e-commerce industry is rapidly evolving, and data-driven decision-making is essential for staying competitive.  

In this project, I built a complete end-to-end data analysis solution using **PostgreSQL, Docker, and Power BI** based on the Northwind dataset.

The project demonstrates how raw data can be stored, managed, transformed, and visualized to generate meaningful business insights.

---

# 🛠️ Data Source & Database Setup (SQL + Docker)

The dataset was loaded into a PostgreSQL database using Docker for efficient environment setup.

## 🔹 Steps Performed

- Used Docker Compose to create:
  - PostgreSQL database container  
  - pgAdmin interface  

- Loaded dataset using the SQL file  

- Connected to database via:
  - pgAdmin (UI)  
  - psql (CLI)  

## 🔹 Database Details

- **Database Name:** northwind  
- **Port:** 55432  

### Tools Used:
- PostgreSQL  
- Docker & Docker Compose  
- pgAdmin  

---

# 🧩 Database Schema

The project uses a relational schema with multiple tables:

- Customers  
- Orders  
- Order Details  
- Products  
- Categories  
- Suppliers  
- Employees  
- Shippers  
- Territories & Region  

## 👉 Relationships

- Customers (1) → Orders (Many)  
- Orders (1) → Order Details (Many)  
- Products (1) → Order Details (Many)  
- Categories (1) → Products (Many)  
- Employees (1) → Orders (Many) 

This schema enables detailed analysis across **sales, products, and customers**.

---

# 🧹 Data Preparation (SQL + Power BI)

## 🔹 In SQL

- Created structured tables using `CREATE TABLE`  
- Inserted data using `INSERT INTO`  
- Verified relationships and schema integrity  
- Queried data using joins for validation  

## 🔹 In Power BI

- Cleaned and transformed data:
  - Fixed data types  
  - Handled null values  
  - Removed inconsistencies  

- Created:
  - Date hierarchy (Year, Quarter, Month)  
  - Calculated columns & measures (DAX)  

---

# 📈 Data Analysis & Insights

## 🔹 Sales Analysis

- Analysed trends by:
  - Year, Quarter, Month, Weekday  

### Key KPIs:
- Total Sales  
- Total Orders  
- Avg Order Value  
- Total Freight  

👉 Insight: Seasonal trends help optimise promotions and inventory planning.

---

## 🔹 Product Analysis

- Identified:
  - Top 5 products by total orders  
  - Category-wise performance  
  - Units in stock vs units on order  

👉 Insight: High-performing categories drive most revenue.

---

## 🔹 Customer Analysis

- Analysed:
  - Active customers  
  - Top customers by sales  
  - Customer distribution by country  

👉 Insight: A small segment of customers contributes a large portion of revenue.

---

## 🔹 Geographic Analysis

- Top countries & cities by:
  - Orders  
  - Customers  
  - Sales  

👉 Insight: Certain regions dominate business performance.

---

# 🎯 Dashboard Features

- Interactive filters (Year, Month, Category, Country, City)  
- Drill-down functionality  
- KPI cards for quick insights  
- Custom UI design with navigation panel  
- Clean dark-themed dashboard  

---

# 🚀 Conclusion

This project showcases an end-to-end data analytics workflow:

- 👉 SQL (Data Storage & Querying)  
- 👉 Docker (Environment Setup)  
- 👉 Power BI (Visualization & Insights)  

It demonstrates how businesses can leverage data to:

- Improve decision-making  
- Identify trends  
- Optimize performance  

---

## 📊 Dashboard Preview

![Dashboard](https://github.com/sahilsekh05/E-commerce-Analysis/blob/main/page1.jpg)
