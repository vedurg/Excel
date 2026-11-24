# 📊 Sales Analysis & Interactive Dashboard

**From raw transactions to actionable business insights.**

A hands-on Microsoft Excel project focused on sales performance, customer behavior, product demand, and regional trends.

---

## 🌟 Project Overview

This project explores a sales dataset using Microsoft Excel to uncover patterns in revenue, transactions, product performance, customer purchases, and regional sales. The workbook brings together spreadsheet formulas, analytical tools, PivotTables, PivotCharts, interactive filters, and a final business report.

The goal is not only to calculate totals, but also to organize the results into a clear story that can help a business understand **what is selling, where revenue is coming from, and which areas may need attention**.

## 📌 Project at a Glance

| Metric | Value |
|---|---:|
| Dataset records | 250 transactions |
| Total revenue | ₹229,192.47 |
| Total quantity sold | 753 units |
| Average order value (AOV) | ₹916.77 |
| Regions analyzed | East, West, Central, North, South |

---

## 🗂️ Dataset Details

The dataset contains transaction-level sales information, including:

| Field | Description |
|---|---|
| Transaction ID | Unique identifier for a transaction |
| Date | Transaction date |
| Customer ID / Customer Name | Customer identification and name |
| Product ID / Product Name | Product identification and product name |
| Category | Product category |
| Quantity | Number of units in the transaction |
| Unit Price | Price per unit |
| Payment Method | Method used to pay |
| Region | Sales region |
| Customer Segment | Customer segment classification |
| Customer Since | Customer start date / tenure context |
| Total Amount | Transaction value |

---

## 🎯 Project Objectives

- Calculate and review the main sales KPIs.
- Explore sales trends across dates and regions.
- Identify high-performing categories and products.
- Understand customer purchasing patterns and identify high-value customers.
- Use formula-based methods to identify frequently purchased products.
- Build interactive summaries and visualizations for easier exploration.
- Present the findings in a concise report with business recommendations.

## 🧰 Excel Skills & Tools Used

| Skill Area | Techniques Used | Purpose |
|---|---|---|
| Formula analysis | COUNTIF, SUMIF, MAX, INDEX, MATCH | Count, summarize, and retrieve information from data |
| Text functions | LEFT, MID, FIND | Create abbreviations from names |
| Date & time | Date/time functions and calculations | Examine dates and time-related values |
| Data summaries | PivotTables | Summarize revenue, quantities, categories, products, and regions |
| Data visualization | Bar, Line, and Pie PivotCharts | Compare results and display trends or distributions |
| Interactive analysis | Slicers and Timeline | Filter PivotTable-based analysis by selected fields and dates |
| KPI presentation | Conditional Formatting, number/currency formatting | Make key metrics easier to scan |
| What-if analysis | Scenario Manager and Goal Seek | Explore changing inputs and target outcomes |
| Statistical analysis | Data Analysis ToolPak — Regression | Examine the relationship between quantity and sales amount |
| Data organization | Remove Duplicates, sorting, copy/paste workflows | Prepare lists and support comparisons |

---

## 📈 KPI Snapshot

| KPI | What it tells us |
|---|---|
| **Total Revenue — ₹229,192.47** | Total sales value recorded in the dataset |
| **Total Transactions — 250** | Number of transaction records analyzed |
| **Total Quantity Sold — 753** | Total units sold across transactions |
| **Average Order Value — ₹916.77** | Average transaction value, calculated as revenue divided by transaction count |

---

## 🔎 Key Findings

| Finding | Result | Business Meaning |
|---|---:|---|
| Highest-revenue region | East — ₹59,288.39 | East contributes the largest revenue among the regions in this dataset |
| Lowest-revenue region | South — ₹36,398.75 | South may be an area to investigate for growth opportunities |
| Leading category | Electronics — ₹171,756.05 | Electronics accounts for a substantial share of recorded revenue |
| Top revenue product | Laptop — ₹67,499.25 | Laptop is the leading product by revenue in this analysis |
| Most frequently purchased product | Bookshelf — 35 occurrences | Bookshelf appears most often in the product purchase count analysis |
| Highest-value customer | Mark Carter — ₹15,659.65 | This customer has the highest recorded purchase total in the analysis |

---

## 💡 Business Recommendations

### 🧭 Regional Strategy
Review the sales approach in the East region to understand what is contributing to its strong revenue. Investigate the South region's lower revenue with additional context—such as customer demand, product mix, transaction volume, and marketing activity—before deciding on changes.

### 🛍️ Product & Category Strategy
Continue monitoring Electronics and leading products such as Laptop. Consider targeted promotions, cross-selling, and stock planning based on observed demand, while checking quantity sold and margins before making inventory decisions.

### 🤝 Customer Engagement
Use the high-value customer analysis to explore loyalty rewards, personalized offers, and retention efforts. Compare purchase frequency and total spend rather than relying on revenue alone when identifying loyal customers.

### 📦 Inventory & Promotion Planning
Use product purchase counts and PivotTable summaries to help plan stock and promotions. Frequently purchased items may require closer stock monitoring, while lower-performing products can be reviewed for pricing, visibility, or bundle opportunities.

---

## 📊 Dashboard & Interactivity

The workbook includes a dashboard-style KPI overview and interactive controls to explore the data:

- **KPI cards:** Total Revenue, Total Transactions, Total Quantity Sold, and Average Order Value.
- **Conditional formatting:** Visual emphasis for KPI values.
- **Slicers:** Region, Category, and Payment Method.
- **Timeline:** Date-based filtering for PivotTable analysis.
- **PivotCharts:** Bar charts for comparisons, a line chart for the monthly trend, and a pie chart for category distribution.

Slicers and Timeline are connected to the PivotTables to support interactive filtering. The charts are organized on the Visualizations sheet, while the Dashboard sheet provides the KPI and filter overview.

---

## 🧭 Workbook Tour

| Sheet | What you'll find |
|---|---|
| **Raw Data** | Original transaction-level dataset |
| **Analysis** | Formula exercises, date/time analysis, what-if tools, regression, storytelling, and customer/product analysis |
| **Pivot Tables** | Regional sales, monthly trend, category distribution, and product quantity summaries |
| **Visualizations** | PivotCharts for regional, monthly, category, and product views |
| **Dashboard** | KPI summary, slicers, and Timeline controls |
| **Final Report** | Summary of the analysis, key findings, and recommendations |

---

## 🧠 Analysis Highlights

### High-Value Customers
Customer purchase totals were summarized to identify customers contributing the most revenue. A Top 10 view and chart were created to make the ranking easier to interpret.

### Product Purchase Frequency
Product names were consolidated into a unique list, purchase occurrences were counted with COUNTIF, and MAX with INDEX/MATCH was used to identify the product with the highest frequency.

### Name Abbreviations
LEFT, MID, and FIND were combined to create initials from full names, demonstrating a simple text transformation workflow.

### Regression Analysis
Regression was performed with the Excel Data Analysis ToolPak to examine the relationship between Quantity and Total Amount. The output was used as a learning exercise in interpreting model statistics and coefficients; it should not be treated as proof of causation or as a forecast without further validation.

---

## 📝 Project Conclusion

This project demonstrates a complete Excel sales-analysis workflow—from working with transaction data and formulas to summarizing results, creating visualizations, and communicating findings. The dashboard and report help make the data easier to explore, while the analysis provides a starting point for business questions about regional performance, product demand, and customer value.

**Tools:** Microsoft Excel 2016 · PivotTables · PivotCharts · Formulas · What-If Analysis · ToolPak Regression

*Built through practice, problem-solving, and plenty of Excel clicks. 💙*
