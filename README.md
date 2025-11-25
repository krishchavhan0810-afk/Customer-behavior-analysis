📊 Customer Shopping Behavior Analysis

A complete end-to-end Data Analytics Project covering data preprocessing (Python), SQL analysis (PostgreSQL), and an interactive Power BI dashboard.
This project helps understand customer spending patterns, product preferences, discount effect, subscription behavior, and overall revenue insights.

🚀 Project Workflow

Dataset – Raw customer shopping dataset (CSV)

Data Cleaning & Prep – Python (Jupyter Notebook)

Database Storage – PostgreSQL

SQL Analytics – Business-driven queries for insights

Dashboard – Interactive Power BI report

🗂️ Project Structure
📁 Customer-Behavior-Analysis
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_query.sql
├── customer_behavior_dashboard.pbix
└── README.md

📌 Objectives

Understand customer purchasing patterns

Identify high-value segments

Compare gender-based revenue

Analyze discounts, ratings & product preference

Evaluate how subscription affects spending

Build a business-ready dashboard for decision making

🛠 Tech Stack
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & preprocessing
PostgreSQL	SQL data storage & analytics
Power BI	Dashboard & visualization
Jupyter Notebook	Exploratory analysis
📑 Key SQL Insights

(Queries sourced from project SQL file) 

customer_behavior_query

1️⃣ Revenue by Gender

Male vs Female revenue comparison using SUM().

2️⃣ High-spending customers using discounts

Filtered customers who used discount and spent above average.

3️⃣ Top 5 Highest Rated Products

Ranked using average review rating.

4️⃣ Standard vs Express Shipping Analysis

Compared avg purchase amounts.

5️⃣ Do Subscribed Customers Spend More?

Outputs:

Total customers

Average spend

Total revenue

6️⃣ Most Discount-Utilizing Products

Top 5 items with the highest discount purchase %

7️⃣ Customer Segmentation

New (1 purchase)

Returning (2–10)

Loyal (>10)

8️⃣ Top 3 Products per Category

Window functions (ROW_NUMBER) used.

9️⃣ Subscription Likelihood Among Heavy Buyers

Repeat buyers (Previous Purchases > 5)

🔟 Revenue Contribution by Age Group

Grouped by “Frequency of Purchases”.

📊 Power BI Dashboard Preview

(Add screenshots in your repo)

Sections included:

Customer Overview

Revenue Analysis

Gender Split

Shipping Type Performance

Discount Impact

Category & Product Insights

Rating Distribution

📈 Key Findings

Female customers generate slightly higher revenue

Discount users still tend to spend above average

Subscription customers contribute major revenue

Express shipping correlates with higher purchase value

Some product categories dominate purchases consistently

Loyal customers show highest lifetime value

🧠 Skills Demonstrated

Data Cleaning & Transformation

SQL Query Optimization

Business Intelligence Reporting

Analytical Problem-solving

Customer Segmentation

DAX & Measures (Power BI)

ETL Workflow Understanding

▶️ How to Run the Project
1. Python Notebook

Install required libraries:

pip install pandas numpy


Run:

jupyter notebook

2. PostgreSQL

Create database

Import CSV

Run queries from:
customer_behavior_query.sql

3. Power BI

Open:

customer_behavior_dashboard.pbix

📬 Contact

For queries or collaboration, feel free to connect!
