# 📊 Product Profit and Sales Analysis

## 🖼️ Dashboard Screenshot

<img width="1438" height="805" alt="image" src="https://github.com/user-attachments/assets/dc707fc7-c5d1-44f4-9d32-24ab2a625038" />

## 📌 Introduction

This project, titled **“Product Profit and Sales Analysis”**, focuses on analyzing business data related to sales, profit, products, and countries.

The dashboard provides a comprehensive view of key performance indicators such as:

* Total Sales
* Profit
* Units Sold

Various visualizations like **bar charts, line charts, and treemaps** are used to represent the data in a clear and interactive way.

The main purpose of this project is to:

* Understand sales patterns
* Identify high-performing products
* Evaluate business performance across different regions

Interactive filters and slicers allow users to dynamically explore data and gain deeper insights, making the dashboard useful for decision-making.

---

## 🎯 Objectives

* To analyze sales and profit data
* To identify top-performing products
* To compare sales across countries
* To visualize data using interactive dashboards

---


## 📂 Dataset Description

The dataset includes the following fields:

* Sales
* Profit
* Country
* Product
* Units Sold
* Discount Band
* Manufacturing Price
* Date (Year, Month)

---

## ⚙️ Steps Performed

1. Imported CSV dataset into Power BI
2. Cleaned data (removed null values, formatted columns)
3. Created relationships (if multiple tables)
4. Designed dashboard layout

### 📊 Visualizations Used

* Bar Chart
* Pie Chart
* Line Chart
* KPI Cards
* Tree Map
* Horizontal Bar Chart
* Slicers

---

## 📈 Dashboard Description

### 🔹 Line Chart

Displays sales variation across countries and highlights trends based on discount bands (high, medium, low, none). Helps understand how pricing strategies impact revenue.

### 🔹 Treemap

Shows hierarchical profit distribution by country and product. Larger blocks indicate higher profit contribution, making it easy to identify top performers.

### 🔹 KPI Cards

Provide a quick summary of business performance:

* Total Profit
* Total Sales
* Total Units Sold
* Gross Sales
* Sale Price

### 🔹 Stacked Column Chart

Compares **gross sales and profit by product**, helping evaluate product efficiency and profit margins.

### 🔹 Clustered Column Chart

Displays product distribution across countries based on production cost. Helps analyze cost variations and profitability.

**DAX Formula Used:**

```
Profit Margin = (Gross Sales - Profit) / Gross Sales
```

### 🔹 Horizontal Bar Chart

Ranks products based on:

* Total Sales
* Sales Average per Country

**DAX Formula Used:**

```
Sales Average per Country = 
AVERAGEX(
    KEEPFILTERS(VALUES('Country')),
    CALCULATE(SUM(Sales))
)
```

### 🔹 Slicers

Interactive slicers allow users to filter data by product, enabling dynamic analysis across all visuals.

---

## ✅ Conclusion

This dashboard provides a clear overview of business performance by combining key metrics such as sales, profit, and units sold.

Key highlights:

* Identifies trends, patterns, and outliers
* Compares performance across countries and products
* Helps identify high-performing regions and products
* Supports better decision-making

Interactive features like slicers and filters enhance user experience and allow deeper data exploration.

Overall, this project demonstrates the importance of **data visualization in modern business environments**, making complex data easy to understand and communicate effectively.

## 👤 Author Details

* **Name:** Jothika K
* **Course:** Data Analytics
