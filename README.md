# 📊 BikeStore Sales Data Analysis Project

This project is a complete data analytics walkthrough inspired by the [Work The Data YouTube tutorial](https://www.youtube.com/watch?v=RDsg75H_J6k), showcasing how to analyze sales data using **SQL Server**, **Excel**, and **Tableau**.

The goal is to simulate a real-world scenario where a data analyst processes raw data into actionable business insights across tools and platforms.

---

## 📁 Project Overview

This project follows a structured data analysis pipeline:

1. **SQL Server** – Data extraction and preparation
2. **Excel** – Dashboard creation with pivot tables and slicers
3. **Tableau** – Advanced visual analytics with interactive dashboards

### 🔗 Reference Tutorial  
📺 [Work The Data – Full Data Analysis Portfolio Exercise (SQL, Excel, Tableau)](https://www.youtube.com/watch?v=RDsg75H_J6k)

---

## 🛠️ Tools Used

| Tool        | Purpose                                      |
|-------------|----------------------------------------------|
| SQL Server  | Create database, run queries, extract data   |
| Excel       | Connect to SQL, build pivot tables/dashboards|
| Tableau     | Create advanced visual and interactive dashboards|

---

## 🔃 Data Setup Instructions

To replicate the project:

1. Download dataset from:  
   📦 https://www.sqlservertutorial.net/wp-content/uploads/2018/03/bike-stores.zip

2. Set up in **SQL Server**:
   - Create new database: `BikeStores`
   - Run the `create objects` script
   - Run the `load data` script

3. [Optional] Use the [Google Sheets Excel version](https://docs.google.com/spreadsheets/d/1M22z-DJhRzTNTpK5J4sKCVT5fD0wrsLDVuXBFXkOrW4/edit) if you're not using SQL Server

---

## 📊 Dashboard Features

### ✅ Excel Dashboard
- Built using **PivotTables**, **PivotCharts**, and **Slicers**
- KPI metrics: **Revenue**, **Total Units**, **Orders**, **Customers**
- Interactive filters for time, region, and category

### ✅ Tableau Dashboard
📈 [View Published Tableau Dashboard](https://public.tableau.com/views/BikeStoreDashboard_17477545872660/Dashboard1)

#### Visuals Included:
- 📅 Revenue by Year (bar chart)
- 👤 Top Customers & Sales Reps (horizontal bar chart)
- 🗺️ Revenue by State (map)
- 🛒 Revenue by Category (tree map)
- 🏬 Revenue by Store (pie chart)
- ⭐ Top Products (table)

---

## 📌 Insights & Recommendations

- **California (CA)** and **Texas (TX)** lead in overall revenue.
- **Mountain Bikes** and **Accessories** are the most profitable categories.
- A few top customers and reps account for a significant share of sales.
- Certain stores underperform despite being in high-revenue regions — consider performance audits or targeted marketing.

---

## ⚠️ Challenges Faced

### 🗺️ Tableau Mapping Issue
Tableau didn’t automatically recognize state abbreviations during map visualization. The issue was resolved by:
- Adjusting geographic roles
- Manually assigning state names or correcting ISO codes

🧾 [Documented in this YouTube video](https://www.youtube.com/watch?v=RDsg75H_J6k)

---

## 🎥 Dashboard Demo (GIF Preview)

![Dashboard Demo](https://github.com/rongxian14/BikeStore-Sales-DA/blob/main/BikeStore%20Dashboard%20Demo.mov)

> 📌 A quick animated walkthrough of the Tableau dashboard. Demonstrates slicers, charts, and interactivity in action.

---

## 🧠 Learning Outcomes

- Hands-on experience with **end-to-end data analytics**
- Developed **SQL** querying and database management skills
- Built **interactive Excel dashboards** using pivot tables and slicers
- Created **advanced Tableau dashboards** with filters, maps, and charts
- Understood how to translate raw data into **business recommendations**

---

## 🗂️ Repository Structure

