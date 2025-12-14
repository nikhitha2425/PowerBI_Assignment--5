# 📈 Sales Performance & Trend Analysis PowerBI-Dashboard

## 📌 Project Summary

This project presents a **professional Power BI analytics dashboard** focused on evaluating **sales performance, profitability, growth trends, and target attainment**.  
It empowers stakeholders to analyze business metrics interactively across **time periods, regions, categories, and products**.

The solution is built using **best practices in Power BI**, including efficient data modeling, optimized DAX measures, and clean report design.

---

## 🎯 Business Goals

- Monitor **overall Sales, Profit, and Quantity**
- Analyze **monthly and annual performance trends**
- Compare **actual sales against predefined targets**
- Highlight **high-performing and underperforming regions and products**
- Support **data-driven strategic decisions** through interactivity

---

## 🗂️ Data Sources

- **Sales.xlsx** – Transactional sales data (orders, products, customers, revenue)
- **Targets.xlsx** – Sales targets by year, region, and category

📌 Excel files act as the **single source of truth** and support refresh in Power BI.

---

## 🔄 Data Preparation (Power Query)

Data was cleaned and transformed using **Power Query**, including:

- Removal of null and duplicate records
- Data type standardization (Date, Numeric, Text)
- Cleaning and splitting of categorical attributes
- Creation of a **Sales Band** column:
  - High (> 100,000)
  - Medium (> 50,000)
  - Low (≤ 50,000)

These steps ensure **clean, consistent, and analysis-ready data**.

---

## 🧩 Data Model Design

A **Star Schema** architecture was implemented for optimal performance.

### Fact Tables
- **FactSales**
- **FactTargets**

### Dimension Tables
- **DimDate** – Enables time intelligence
- **DimYear** – Supports target comparisons
- **DimRegion** – Avoids many-to-many relationship ambiguity

✔ One-to-many relationships  
✔ No fact-to-fact joins  
✔ Optimized and scalable model  

---

## 🧮 DAX Calculations

### Core Measures
- Total Sales  
- Total Profit  
- Total Quantity  
- Total Target  

### Time Intelligence Measures
- Sales YTD  
- Sales Last Year (LY)  
- Year-over-Year (YoY) Growth %

Measures were preferred over calculated columns for **performance and reusability**.

---

## 📊 Report Pages Overview

### 1️⃣ Executive Overview
- KPI Cards: Sales, Profit, YoY Growth
- Donut Chart: Sales by Category
- Ribbon Chart: Category Rank Over Time
- Line Chart: Monthly Sales Trend

### 2️⃣ Trend Insights
- Sales and Profit trends
- Line & Stacked Column Chart
- Regional Sales Map

### 3️⃣ Product Performance Analysis
- Matrix: Category → Subcategory → Product
- Conditional formatting using data bars and color scales
- Top-N product performance insights

### 4️⃣ Sales Trend (R Script Visual)
- Custom R visual for sales trend analysis
- Line plot showing sales distribution over time
- Demonstrates advanced analytics integration in Power BI

---

## 🔍 Interactivity & Filters

- Report-level slicers: **Year, Region, Category**
- **Q&A Visual** for natural language queries
- Cross-filtering and drill-down enabled across visuals

---

## 🚀 Advanced Capabilities

- Natural language analytics using Q&A
- Interactive visuals with drill-down support
- Enterprise-ready data model and DAX logic

---

## 📦 Project Files

- `Sales_Performance_Trend_Analysis.pbix`
- `Sales.xlsx`
- `Targets.xlsx`
- `README.md`
- `Results`

---

## ✅ Conclusion

This dashboard delivers a **robust, scalable, and interactive BI solution** for monitoring sales and performance metrics.  
It highlights strong expertise in **Power BI, DAX, Power Query, data modeling, and visualization best practices**.

---

## 👤 Author

**Nikhitha**
