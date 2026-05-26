# 📊 Amazon Sales Report Dashboard

> An interactive Power BI dashboard built on the Superstore Dataset to analyze Amazon's global sales performance, profit trends, and product insights across multiple markets and customer segments.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Data Cleaning & Transformation](#data-cleaning--transformation)
- [Dashboard Features](#dashboard-features)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Key Insights & Findings](#key-insights--findings)
- [Tools & Technologies Used](#tools--technologies-used)
- [Dashboard Preview](#dashboard-preview)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## 📖 Project Overview

This project presents a comprehensive **Sales Performance Dashboard** built in Power BI, designed to provide actionable business intelligence from Amazon's global sales data. The dashboard enables stakeholders to monitor revenue performance, track profitability, identify top-performing products and markets, and understand customer segment behavior — all through a single, interactive visual interface.

**Business Questions Answered:**
- Which product categories and segments drive the most revenue?
- What are the monthly sales trends over the years?
- Which countries and markets contribute the highest sales?
- Which individual products are the top revenue generators?

---

## 📂 Dataset Description

| Attribute         | Details                                |
|-------------------|----------------------------------------|
| **Source**        | Superstore Dataset                     |
| **Total Rows**    | 51,291 (including header)              |
| **Total Columns** | 24                                     |
| **Years Covered** | 2011 – 2014                            |
| **Markets**       | Africa, APAC, Canada, and more         |
| **Categories**    | Furniture, Office Supplies, Technology |

**Key Columns Include:**
- `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`
- `Customer Name`, `Segment`, `Country`, `Market`
- `Category`, `Sub-Category`, `Product Name`
- `Sales`, `Quantity`, `Discount`, `Profit`

---

## 🧹 Data Cleaning & Transformation

All data cleaning and transformation was performed using **Power Query** in Power BI before building the data model.

Steps performed:
- Removed duplicate records and irrelevant rows
- Handled null/missing values in key columns
- Corrected inconsistent data types (dates, currency, integers)
- Standardized column names for readability
- Created calculated columns for Profit Margin %
- Filtered and validated data across all 24 columns for accuracy

---

## 📊 Dashboard Features

The dashboard includes the following interactive visualizations:

| Visual                       | Description                                                |
|------------------------------|------------------------------------------------------------|
| **KPI Cards**                | Total Sales, Total Profit, Total Orders, Profit Margin %   |
| **Sales by Category**        | Bar chart comparing Technology, Furniture, Office Supplies |
| **Sales by Segment**         | Donut chart — Consumer, Corporate, Home Office             |
| **Monthly Sales Trend**      | Line chart showing sales pattern across all 12 months      |
| **Top 5 Countries by Sales** | Horizontal bar chart of highest revenue-generating nations |
| **Top 5 Products by Sales**  | Horizontal bar chart of best-selling individual products   |

**Interactive Filters (Slicers):**
- Filter by **Category** (Furniture, Office Supplies, Technology)
- Filter by **Market** (Africa, APAC, Canada, etc.)
- Filter by **Order Date / Year** (2011, 2012, 2013, 2014)

---

## 📈 Key Performance Indicators (KPIs)

| KPI                | Value   |
|--------------------|---------|
| **Total Sales**    | $12.64M |
| **Total Profit**   | $1.47M  |
| **Total Orders**   | 25K     |
| **Profit Margin**  | 11.61%  |

---

## 💡 Key Insights & Findings

1. **Technology leads in Sales** — Technology is the top-selling category at $4.7M, followed by Furniture ($4.1M) and Office Supplies ($3.8M).

2. **Consumer Segment dominates** — The Consumer segment accounts for 51.3% ($2.78M) of total sales, making it the largest customer segment, ahead of Corporate (30.5%) and Home Office (18.2%).

3. **United States is the top market** — The US generates $2.3M in sales, significantly outperforming Australia and France (both at $0.9M), China ($0.7M), and Germany ($0.6M).

4. **Sales peak in Q4** — The Monthly Sales Trend shows a consistent upward trajectory from mid-year, with the highest sales occurring in November and December, indicating strong seasonal demand.

5. **Smartphones dominate product sales** — The Apple Smart Phone, Full Size ($87K) is the single best-selling product, followed by Cisco ($76K), Motorola ($73K), and Nokia ($72K) smartphones.

---

## 🛠️ Tools & Technologies Used

| Tool                   | Purpose                                    |
|------------------------|--------------------------------------------|
| **Power BI**           | Dashboard development & data visualization |
| **Power Query**        | Data cleaning & transformation             |
| **DAX**                | Calculated measures (Profit Margin %, KPIs)|
| **Superstore Dataset** | Primary data source                        |

---

## 🖼️ Dashboard Preview

![Amazon Sales Report Dashboard](dashboard_preview.png)

---

## 🔮 Future Improvements

- Add **Return Rate Analysis** to track product return trends
- Include **Year-over-Year (YoY) growth** comparison metrics
- Add **profitability by Sub-Category** drill-through page
- Integrate **forecasting visuals** for future sales prediction
- Publish dashboard to **Power BI Service** for online access

---

## 👤 Author

**Yogesh Patra**

- 💼 LinkedIn: [yogesh-patra](https://www.linkedin.com/in/yogesh-patra-b10b20286)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> ⭐ If you found this project helpful, please consider giving it a star on GitHub!
