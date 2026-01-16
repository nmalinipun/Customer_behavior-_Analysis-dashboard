
# Customer Behavior Analysis Dashboard (Python + SQL + Tableau)

This project is an end-to-end customer shopping behavior analysis using **Python**, **SQL (MySQL)**, and **Tableau Public**.  
It covers data cleaning, analytical querying, and dashboard visualization.

---

## 📌 Project Overview
The goal of this project is to understand customer purchase behavior and key business insights such as:
- Total customers
- Average purchase amount
- Average review rating
- Revenue & sales trends by product category
- Customer segmentation (age group, gender)
- Subscription behavior analysis

---

## 🛠️ Tools Used
- **Python (Pandas, NumPy)** → Data cleaning + feature engineering
- **MySQL (SQL queries)** → Data exploration + aggregation + validation
- **Tableau Public** → Interactive dashboard building and visualization

---

## 📂 Dataset
Customer shopping dataset (CSV) containing fields like:
Customer ID, Age, Gender, Category, Item Purchased, Purchase Amount (USD), Review Rating, Subscription Status, Shipping Type, Payment Method, etc.

---

## 🔄 Workflow (What I did)
### 1) Python (Cleaning + Feature Engineering)
Using Python, I cleaned the dataset and created useful new features:
- Converted Yes/No values into binary (1/0)
- Converted numeric fields properly (Age, Purchase Amount, Rating)
- Created **Age Group**
- Created **Purchases Per Year**
- Created **High Spender flag (Top 25%)**
- Added missing-rating indicator

✅ Output: cleaned CSV used for analysis and Tableau

---

### 2) SQL (Analysis + Insights)
The cleaned data was loaded into **MySQL**, and SQL was used to:
- Aggregate revenue by category
- Count subscription status customers
- Analyze purchase patterns by age group and gender
- Validate KPIs using database queries

✅ SQL helps when working with large datasets and reproducible analytics.

---

### 3) Tableau (Dashboard)
Built an interactive Tableau dashboard with:
✅ KPI Cards:
- **Total Customers**
- **Average Purchase Amount**
- **Average Review Rating**

✅ Visuals:
- Revenue by Category
- Sales by Category
- Subscription Status Pie (Yes vs No)
- Revenue by Age Group
- Gender Distribution
- Top Products

✅ Filters:
- Subscription Status (Yes/No)

---

## 📊 Dashboard Preview
(You can add screenshots here)
- `images/dashboard.png`

---

## 📁 Repository Files
- `customerr.csv` → dataset used in Tableau
- `clean_customer_shopping.py` → Python data cleaning script
- `customer behavior.sql` → SQL analysis queries
- `customer_behavior_analysis.twb` → Tableau workbook file

---

## ▶️ How to Run (Optional)
### Run Python cleaning
```bash
python clean_customer_shopping.py
