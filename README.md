# 📊 Northwind Revenue Insights – H1 2006

## 📌 Overview
**SQL & Power BI-based quantitative analysis** of Northwind Traders sales data for the first half of 2006.  

The project uncovers **sales performance trends, product concentration risks, and employee-level operational insights**, providing actionable business intelligence for strategic decisions.  

Demonstrates **data extraction, transformation, visualization, and reproducible analysis workflows** for operational datasets.

---

## ⚙️ Workflow

### 1️⃣ System Recognition
- **Domain:** Retail sales and operational performance analysis  
- **Goal:** Identify top-performing products, categories, and employees; detect revenue concentration risks  
- **Constraint:** Ensure reproducible analysis across raw SQL data and Power BI visualizations

### 2️⃣ Data Collection
- Source: **Northwind Traders H1 2006 sales database**  
- Extract raw data via **SQL queries**  
- Store datasets in `data/` for reproducibility

### 3️⃣ Data Cleaning & Transformation
- Standardize column names, data types, and formats  
- Deduplicate records and ensure chronological integrity  
- Aggregate data at **monthly, product, and employee levels**

### 4️⃣ Exploratory Analysis
- Compute **key performance indicators (KPIs)**: Total Revenue, Total Orders, Total Customers, Average Order Value  
- Analyze **top products, categories, and employee contributions**  
- Detect **high revenue concentration** and potential operational bottlenecks

### 5️⃣ Visualization
- Build **Power BI dashboards** for interactive analysis  
- Star schema model: **fact_sales** at center with dimensions for Products, Categories, Employees, Customers  

**Power BI Model View:**  
![Model View](power_bi/model_view.png)  

**Dashboard Preview:**  
![Dashboard Preview](power_bi/dashboard_preview.png)

### 6️⃣ Insights
- **Total Revenue:** $13M  
- **Top Products Revenue Share:** ~64% concentrated in 3 products  
- **Category Focus:** Beverages & Seafood dominate sales  
- **Employee Impact:** Significant variation; top performers’ strategies could be standardized

> The workflow ensures **scalable, reproducible, and actionable analysis** of sales data.

---

## 🚀 Key Features

| Feature | Technique / Concept |
|---------|-------------------|
| Sales KPI Analysis | Total revenue, orders, customers, AOV |
| Product & Category Insights | Revenue concentration, top-performing items |
| Employee Contribution | Identify and replicate best practices |
| Data Transformation | SQL queries for extraction & aggregation |
| Interactive Visualization | Power BI dashboards and model view |
| Reproducible Workflow | Structured scripts & dataset management |

---

## 🛠️ How to Run
1. Place **raw Northwind H1 2006 SQL data** in the `data/` folder  
2. Run **SQL queries** in `sql/northwind_queries.sql` for extraction and transformation  
3. Open **Power BI dashboard** (`power_bi/northwind_dashboard.pbix`) for interactive analysis  
4. Outputs include **cleaned datasets, KPIs, and visual dashboards**
