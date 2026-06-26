# Wholesale Sales Performance &amp; Demand Planning End-to-End Analytics Project


### An end-to-end analytics project that simulates the responsibilities of a Sales Analyst at a wholesale manufacturing company. This project demonstrates how SQL, Excel, and Python can be used together to transform transactional sales data into actionable business insights, interactive dashboards, demand forecasts, and executive-level recommendations.
---

# Project Overview

Wholesale manufacturers rely on data to optimize revenue, profitability, inventory planning, and customer performance. This project recreates a realistic business workflow using a simulated two-year wholesale sales dataset containing over 5,000 wholesale orders.

The analysis follows the complete analytics lifecycle:

* Data preparation
* Business reporting with SQL
* Executive dashboard development in Excel
* Demand forecasting using machine learning
* Business recommendations supported by quantitative analysis

---

# Business Problem

Wholesale manufacturers regularly need to answer questions such as:

* Which customers generate the highest revenue?
* Which product categories are most profitable?
* Which regions are driving growth?
* Are promotional discounts increasing overall profitability?
* How concentrated is revenue among major accounts?
* What inventory levels should be planned for the next quarter?

This project demonstrates how data analytics can answer these questions using realistic business data.

---

# Project Objectives

The primary objectives of this project are to:

* Analyze historical wholesale sales performance
* Identify revenue and profit drivers
* Evaluate promotional effectiveness
* Measure customer and regional performance
* Forecast future product demand
* Deliver actionable recommendations for leadership

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| SQL | Business reporting and KPI analysis |
| Microsoft Excel | Executive dashboard and interactive reporting |
| Python | Data generation, analysis, forecasting, and automation |
| XGBoost | Machine learning demand forecasting |
| Pandas | Data preparation and feature engineering |
| Git & GitHub | Version control and portfolio presentation |

---

# Dashboard

The Excel dashboard provides an executive overview of business performance through interactive KPIs and visualizations.

### Dashboard Features

* Revenue by month
* Gross margin trends
* Sales by region
* Product category performance
* Top wholesale customers
* Promotion performance
* Sales contribution analysis
* Interactive slicers and filters

> **Dashboard screenshots will be added here**

---

# Business Questions Answered

This project addresses several common business questions faced by wholesale sales organizations.

### Sales Performance

* How has revenue changed over time?
* Which months generate the highest sales?
* What are overall gross margins?

### Customer Analytics

* Who are the highest-value customers?
* How concentrated is company revenue?
* Which customers are growing the fastest?

### Product Performance

* Which products generate the highest sales?
* Which categories produce the greatest profit?
* Which products underperform?

### Regional Analysis

* Which sales regions outperform expectations?
* Which regions require additional investment?

### Promotion Analysis

* Do discounts increase total profitability?
* What is the financial impact of promotional campaigns?

### Demand Planning

* What sales volume should be expected next quarter?
* Which products require additional inventory planning?

---

# Key Results

| Metric | Result |
|---------|---------|
| Simulated Revenue | **$8.1M** |
| Wholesale Orders | **5,098** |
| Wholesale Customers | **40** |
| Sales Regions | **5** |
| Forecast Accuracy (MAPE) | **33%** |
| Promotion Impact | Representative Q4 promotion scenario reduced gross margin by approximately **$321K (22%)** compared with full-price sales, indicating the assumed discount depth outweighed the additional volume generated. |

---

# Project Workflow

```text
Raw Sales Data
        │
        ▼
Data Cleaning & Validation
        │
        ▼
SQL Business Analysis
        │
        ▼
Executive Excel Dashboard
        │
        ▼
Demand Forecasting (Python + XGBoost)
        │
        ▼
Business Insights & Recommendations
```

---

# Repository Structure

```text
wholesale-sales-performance-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── sql/
│   ├── business_queries.sql
│   └── kpi_analysis.sql
│
├── python/
│   ├── generate_data.py
│   ├── forecasting.py
│   └── analysis.ipynb
│
├── dashboard/
│   └── Wholesale_Sales_Performance_Dashboard.xlsx
│
├── images/
│   └── dashboard_screenshots/
│
├── README.md
└── requirements.txt
```

---

# Executive Insights

The analysis highlights several business opportunities:

* Revenue is concentrated among a relatively small number of wholesale accounts, indicating customer concentration risk.
* Regional performance varies significantly, revealing opportunities for targeted sales investment.
* Promotional discounts can increase unit sales while reducing total gross margin if discount depth exceeds incremental demand.
* Demand forecasting provides a data-driven foundation for inventory planning and purchasing decisions.

---

# Business Value

This project demonstrates how modern analytics can support strategic decision-making by:

* Improving revenue visibility
* Monitoring profitability
* Evaluating pricing strategies
* Optimizing inventory planning
* Supporting executive reporting
* Reducing manual reporting effort

---

# Skills Demonstrated

* Business Analytics
* Sales Analytics
* SQL
* Microsoft Excel
* Dashboard Design
* Data Visualization
* KPI Development
* Forecasting
* Machine Learning
* Python
* Data Cleaning
* Executive Reporting
* Business Communication

---

# Future Improvements

Potential enhancements include:

* Power BI dashboard
* Customer segmentation using clustering
* Price elasticity modeling
* Inventory optimization
* Time-series forecasting with Prophet and LightGBM
* Automated ETL pipeline
* Cloud data warehouse integration
* dbt transformation pipeline

---

## Author

**Matthew Trigg**
