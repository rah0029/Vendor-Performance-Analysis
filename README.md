# Vendor-Performance-Analysis

## 🧠 Business Problem

Retailers and wholesalers often face challenges related to:
- Inefficient vendor performance
- Excess or unsold inventory
- Poor pricing strategies
- Low profit margins and high operational costs

The goal of this project is to help companies (like Amazon or Walmart) **optimize vendor selection, pricing, and stock management** by analyzing historical purchase, sales, inventory, and vendor invoice data.

---

## 🧭 Project Workflow

1. **Business Understanding** – Focused on vendor performance and inventory efficiency  
2. **Data Ingestion** – Multiple large CSVs (sales, purchases, inventory, invoices) imported into SQLite  
3. **Data Cleaning & Aggregation** – Final summary table created as a unified data source  
4. **Exploratory Data Analysis (EDA)** – Conducted using Python to reveal trends and performance patterns  
5. **Feature Engineering** – Created metrics like gross profit, profit margin, and stock turnover  
6. **Statistical Testing** – Hypothesis testing and confidence intervals used to validate findings  
7. **Visualization & Reporting** – Power BI dashboard built to present actionable insights to stakeholders  

---

## 🛠️ Tools & Technologies Used

- **SQL (SQLite)** – Data ingestion, joins, aggregation, and performance optimization  
- **Python (Pandas, Matplotlib, Seaborn, SciPy)** – EDA, feature creation, and statistical analysis  
- **Power BI** – Interactive dashboard to present KPIs and vendor/brand insights  
- **Logging & Reusability** – Scripts built with logging and modular design for real-world reuse  
- **Documentation** – Complete report writing with screenshots and insights for stakeholders

---

## 📌 Project Highlights

- 📊 Real-world retail/wholesale use case focused on profit and efficiency  
- 💡 Business-driven questions like identifying underperforming vendors, cost-saving strategies, and capital lock-up  
- ⚙️ Query optimization techniques used to handle datasets with over **1 crore records**  
- 🧠 Insights supported with statistical evidence (e.g., bulk purchases reduce unit costs significantly)  
- 📈 Power BI dashboard includes dynamic visuals such as KPI cards, funnel charts, and scatter plots  
- 📋 Final report includes findings, actions, and business recommendations

---

## 📈 Key Insights & Impact

- **Top-performing vendors** contribute most to purchases but not always to profits  
- **Bulk purchasing** significantly reduces unit costs, validating economies of scale  
- **Low-performing brands** with high margins indicate premium pricing strategies  
- **Excess inventory** causes capital to be locked, highlighting need for smarter restocking  
- **Interactive dashboards** enable stakeholders to identify issues and take real-time action  
- **Scalable queries** and reusable Python scripts make the pipeline efficient for future use

---

## 💼 Why This Project Matters

This project mirrors what real companies expect from data analysts:
- Ability to work with **large, messy, multi-table datasets**
- Use of **multiple tools across the analytics stack**
- Delivering **data-backed business insights**, not just visualizations
- Clear **storytelling and communication** through dashboards and reports
