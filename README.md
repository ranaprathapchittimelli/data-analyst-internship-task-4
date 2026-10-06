#  Sales & Financial Analysis Dashboard – Power BI

##  Project Overview

This project is a **Sales & Financial Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze sales performance, revenue, profit, territories, product lines, and quarterly trends using data visualization and business intelligence techniques.

The dashboard helps identify important business insights and supports data-driven decision-making.

---

## Objectives

- Analyze overall sales and financial performance.
- Track total revenue and profit.
- Compare revenue across different territories.
- Analyze performance by product line.
- Identify revenue and profit trends over time.
- Compare quarterly performance.
- Calculate and analyze profit margin.
- Create an interactive and easy-to-understand dashboard.

---

##  Tools & Technologies

- **Microsoft Power BI**
- **Microsoft Excel**
- **DAX**
- **Data Visualization**
- **Data Analysis**

---

##  Dataset

The dataset contains sales and financial information including:

- Order Date
- Month
- Quarter
- Territory
- Product Line
- Customer
- Revenue
- Profit

---

##  Dashboard Visualizations

The Power BI dashboard contains the following visualizations:

###  KPI Cards

- Total Revenue
- Total Profit
- Total Orders
- Profit Margin

###  Charts

1. **Revenue Trend by Date** – Line Chart
2. **Revenue by Territory** – Column Chart
3. **Profit by Territory** – Bar Chart
4. **Revenue by Product Line** – Donut Chart
5. **Revenue by Quarter** – Column Chart
6. **Revenue vs Profit Analysis** – Chart

---

##  DAX Measures

### Total Revenue

```DAX
Total Revenue = SUM(Sheet1[Revenue])
