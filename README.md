# Ecommerce_data_analytics_project
-projects1,2,3

## Overview
This repository contains three progressive data analytics projects completed as part of the DecodeLabs Data Analytics Bootcamp (Batch 2026). Each project builds on the same core dataset — an e-commerce orders dataset — moving from data cleaning, to exploratory analysis, to SQL-based business analysis.

| Project | Focus | Tool(s) |
|---|---|---|
| [Project 1](./project1-data-cleaning) | Data Cleaning & Preparation | VS Code / Python |
| [Project 2](./project2-eda) | Exploratory Data Analysis (EDA) | Python (pandas), Microsoft Copilot |
| [Project 3](./project3-sql-analysis) | SQL Data Analysis | MySQL Workbench 8.0 |

---

## Project 1: Data Cleaning & Preparation
Cleaned and prepared the raw e-commerce orders dataset for downstream analysis — handling formatting issues, inconsistent values, and preparing the data for EDA and SQL work in Projects 2 and 3.

**Details:** see [`project1-data-cleaning/README.md`](./project1-data-cleaning/README.md)


---

## Project 2: Exploratory Data Analysis (EDA)
Performed EDA on the e-commerce orders dataset (~105KB, thousands of rows) covering: OrderID, Date, CustomerID, Product, Quantity, UnitPrice, ShippingAddress, PaymentMethod, OrderStatus, TrackingNumber, ItemsInCart, CouponCode, ReferralSource, TotalPrice.

**Key findings:**
- No duplicate OrderIDs
- Missing values present in `CouponCode` and `ReferralSource`
- `PaymentMethod` had inconsistent labeling (e.g. "Online" vs "Credit Card") but no missing values

**Details:** see [`project2-eda/README.md`](./project2-eda/README.md)

---

## Project 3: SQL Data Analysis
Used SQL (MySQL Workbench 8.0) to extract business insights from the same orders dataset (1,200 rows) using `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `HAVING`, and aggregate functions.

**Highlights:**
- Only 58.6% of orders completed successfully; cancellations and returns cost ~₹5.2 lakh in lost revenue
- Product revenue is evenly distributed across the catalog (no single dominant product)
- Instagram is the top-performing referral channel
- Tablets have the highest return rate (24%)
- Top-spending customers are one-time buyers, not repeat customers

**Details:** see [`project3-sql-analysis/README.md`](./project3-sql-analysis/README.md)

---

## Repository Structure
```
decodelabs-data-analytics-bootcamp/
├── README.md                      ← this file
├── project1-data-cleaning/
│   └── README.md
├── project2-eda/
│   └── README.md
└── project3-sql-analysis/
    ├── data_analysis.sql
    ├── README.md
    └── screenshots/
```

---

## About
These projects were completed as part of the DecodeLabs Data Analytics Bootcamp, building foundational skills in data cleaning, exploratory data analysis, and SQL for a Data Analyst career path.
