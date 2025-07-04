# 📊 Retail-Sales-and-Dashboard-in-Excel

## 📁 Project Overview

This project demonstrates end-to-end data analysis and dashboard creation using Microsoft Excel. The goal is to analyze and visualize sales data for a fictional retail company to uncover trends, evaluate performance, and provide actionable insights.

---

## 🎯 Objective

- Clean and transform raw sales data
- Perform basic business analytics using Excel formulas and pivot tables
- Build an interactive dashboard with slicers and KPIs
- Develop insights into sales by region, product category, and sales reps

---

## 📂 Dataset Structure

The dataset contains 8 records of sales transactions with the following columns:

| Column Name       | Description                          |
|-------------------|--------------------------------------|
| Order ID          | Unique identifier for each order     |
| Order Date        | Date the order was placed            |
| Region            | Sales region                         |
| Sales Rep         | Name of the salesperson              |
| Product Category  | Category of the product              |
| Product           | Product name                         |
| Units Sold        | Quantity sold                        |
| Unit Price        | Price per unit                       |
| Profit            | Net profit from the order            |

### ➕ Calculated Columns:

| New Column       | Formula                                 | Purpose                                 |
|------------------|------------------------------------------|-----------------------------------------|
| Total Sales      | `=Units Sold * Unit Price`              | Revenue per order                       |
| Month            | `=TEXT(Order Date, "mmm yyyy")`         | Extracted month for trend analysis      |
| Profit Margin    | `=Profit / Total Sales`                 | Profitability per order                 |

---

## 🛠️ Tools & Features Used

- Microsoft Excel
- Excel Tables (`SalesTable`)
- Pivot Tables & Pivot Charts
- Slicers (for interactivity)
- Conditional Formatting
- Dashboard Design

---

## 🧠 Key Insights Delivered

- **Top-Performing Regions**: Identified based on total sales.
- **Most Profitable Products**: Tracked using profit margin.
- **Sales Rep Performance**: Compared sales and profits by rep.
- **Monthly Trends**: Visualized using line and column charts.

---

## 📌 Skills Demonstrated

- 📈 Data Cleaning & Preprocessing  
- 📊 Pivot Tables & Dynamic Charts  
- 🎛️ KPI Card Design & Dashboard Layout  
- 📅 Time-Based Trend Analysis  
- 📎 Business Insight Communication

---

## 📸 Dashboard Preview

*(Insert a screenshot of your final dashboard here in the GitHub repository)*

---

## 📝 How to Use

1. Download or clone the repository.
2. Open `Retail_Sales_Dashboard.xlsx` in Microsoft Excel (2021 or Office 365 recommended).
3. Explore the `SalesData` sheet to view raw data and calculations.
4. Go to the `Dashboard` sheet to interact with slicers and view insights.

---

## 🤝 Connect

If you like this project or want to collaborate, feel free to connect:

- 📧 Email: praneethkumarreddy952@gmail.com  
- 🔗 LinkedIn: [https://www.linkedin.com/in/praneethrdy]

---

## 📌 License

This project is for educational and portfolio purposes only. Feel free to fork and build upon it.

---
