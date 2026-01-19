Got it 👍
Below is a **complete but still short & meaningful README** — **no over-explanation**, clean and professional.

---

# 📊 Vendor Sales Business Analytics

## 📌 Project Overview

This project performs **vendor-level sales, purchase, and inventory analysis** using data stored in **PostgreSQL**.
Python is used for **EDA, business analytics, and statistical analysis**, and insights are visualized using **Power BI** to support data-driven decisions.

---

## 🗄️ Data Source

Data is fetched from a PostgreSQL database (`inventory_db2`) and mainly uses the **`vendor_sales_summary`** table, which consolidates:

* Purchases
* Sales
* Vendor invoices (freight)
* Product pricing

---

## 🔄 Data Pipeline Flow

```
PostgreSQL Tables
        ↓
Vendor Sales Summary Table (SQL Aggregations)
        ↓
Python (EDA + Business Analytics)
        ↓
Statistical Analysis
        ↓
Power BI Dashboard
```

---

## 🛠️ Tech Stack

* **Database:** PostgreSQL
* **Programming Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, scipy
* **DB Connectivity:** psycopg2, SQLAlchemy
* **Visualization & Reporting:** Power BI

---

## 🔍 Analysis Performed

* Exploratory Data Analysis (EDA)
* Vendor & brand performance analysis
* Gross profit & profit margin analysis
* Inventory turnover & unsold inventory value
* Bulk purchase impact on unit price
* Pareto (80/20) vendor contribution analysis
* 95% confidence interval analysis for profit margins

---

## 📊 Power BI Dashboard Overview

The Power BI dashboard is built using `vendor_sales_summary` and includes:

* KPI cards (Sales, Purchases, Profit, Margin)
* Top vendors and brands by sales
* Vendor contribution (Pareto analysis)
* Inventory & stock turnover analysis
* Profitability and risk insights

---

## 💡 Key Business Insights

* Bulk purchasing significantly reduces unit cost.
* Few vendors contribute most of the procurement value.
* High sales do not always mean high profitability.
* Slow-moving inventory locks substantial capital.

---

## ▶️ How to Run

```bash
python vendor_sales_business_analytics.py
```

---

## 🎯 Use Case

* Data Analyst / Business Analyst portfolio
* Inventory & supply chain analytics
* SQL + Python + Power BI project


