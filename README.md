# 📊 Retail Store Data Analysis (Power BI)

## 📁 Project Overview
This project focuses on analyzing retail store sales data using **Microsoft Power BI**.  
The goal was to answer key business questions from the **CEO** and **CMO** by creating interactive dashboards with cleaned and reliable data.

The project includes:
- ✅ Data cleaning & transformation
- ✅ Four Power BI visuals (one per business question)
- ✅ Actionable insights for business decision-making

> 📌 **Note:** The dataset used for this project was provided as part of the  
[Tata Data Visualization: Empowering Business with Effective Insights (Forage Virtual Internship)](https://www.theforage.com/).  

---

## 🧹 Data Cleaning
Before creating the visuals, the dataset was cleaned using Power BI’s **Power Query Editor**:

1. **Quantity Check** → Removed rows where `Quantity < 1` (negative values represented returns).
2. **Unit Price Check** → Removed rows where `UnitPrice < 0`.
3. **Transformation** → Applied conditional filters in Power Query to exclude invalid rows.

👉 After cleanup, the dataset contained only valid sales transactions for analysis.

---

## 🔎 Business Questions & Visuals

### **Question 1: Monthly Revenue Trends (2011)**
- **Goal:** CEO wanted to view revenue trends for 2011 by month.
- **Visual:** Line chart showing monthly revenue.
- **Insight:** Seasonal trends identified, useful for forecasting.

---

### **Question 2: Top 10 Countries by Revenue (Excluding UK)**
- **Goal:** CMO wanted to analyze the top 10 countries by revenue & quantity sold, excluding UK.
- **Visual:** Bar chart with dual-axis (Revenue & Quantity).
- **Insight:** Highlights high-performing countries for regional strategies.

---

### **Question 3: Top 10 Customers by Revenue**
- **Goal:** CMO wanted to identify top 10 customers to target with retention strategies.
- **Visual:** Sorted bar chart with descending revenue (highest → lowest).
- **Insight:** Reveals the customers contributing the most to revenue.

---

### **Question 4: Regional Demand (Excluding UK)**
- **Goal:** CEO wanted to see demand distribution by country (excluding UK) to guide expansion.
- **Visual:** Filled map showing product demand by country.
- **Insight:** Identifies regions with high potential for business expansion.

---

## 🛠 Tools Used
- **Microsoft Power BI Desktop (.pbix)**
- **Power Query Editor** (data cleaning & transformation)
- **DAX** (basic calculations where required)
- **Excel/CSV Data Source** (provided via Tata Virtual Internship)

---

## 📂 Repository Contents
- `Retail_Analysis.pbix` → Power BI project file
- `README.md` → Project documentation (this file)
- `data/` → Raw Dataset


---

## 🎯 Key Learnings
- Hands-on experience with **data cleaning in Power Query**.
- Building **business-ready dashboards** for C-level executives.
- Using Power BI to turn raw data into **clear, actionable insights**.
- Developing skills in **data storytelling, visualization, and business analysis**.

---

✨ This project demonstrates the ability to **analyze, visualize, and present data effectively in Power BI** for real business decision-making.
