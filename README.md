# 📊 Business Intelligence Portfolio

Welcome to my Business Intelligence portfolio. This repository showcases Power BI dashboards focused on sales analytics, revenue reporting, profitability analysis, and executive business intelligence. 

These projects demonstrate my ability to take messy, real-world-style data and turn it into clean, interactive dashboards that support decision-making — with an emphasis on getting the data quality right before the visuals go on top.

---

## 🚀 The Business Problem
Leadership teams often can't trust a single number on their own dashboard — not because the visuals are wrong, but because the data feeding them is inconsistent: the same region spelled three different ways, duplicate orders inflating totals, a revenue column that silently breaks when a source system changes. The result is slow, distrusted reporting instead of fast, confident decisions.

Each project below starts from that kind of messy, unreconciled data and works through to a decision-ready dashboard — the data-cleaning decisions are documented alongside the visuals, not hidden behind them.

---

## 💡 KPI Definitions

*   **Revenue (DAX measure):** Rebuilt at the measure level from transaction data rather than trusted from a pre-aggregated source column — the source column was found to be unreliable, so the calculation logic is explicit and auditable instead of a black box.
*   **Profit Margin (%):** `(Revenue − Cost) / Revenue`, used to compare profitability consistently across regions, categories, and products once the underlying data was cleaned.
*   **Data Completeness Flag:** Rather than silently dropping incomplete records, ambiguous or missing values (e.g. ~8% of region data in Project 01) are flagged and kept visible in the model — a documented data-quality decision, not a hidden gap.

---

## 📁 Featured Projects

### 📌 01 – Enterprise Revenue Analytics
Executive dashboard built from a 1,242-row, 21-column global sales dataset. Cleaning work included removing duplicate orders, standardizing inconsistent region names across two Power Query passes, filtering out invalid negative quantities, and rebuilding Revenue as a DAX measure rather than trusting a broken source column. ~8% of rows had missing region data — flagged and kept visible rather than silently dropped. Final dashboard tracks Total Revenue, Total Profit, Total Orders, and Profit Margin, broken down by Month, Region, Product, and Category.

### 📌 02 – Product Profitability Deep Dive
Dashboard analyzing retail order data with a focus on profitability: discount-vs-profit relationships, sales trends by order date, top-performing products, average delivery days, and profit by sub-category, with a year slicer for period comparison.

### 📌 03 – Global Sales Executive Command Center
Executive-level view of global sales performance: revenue growth trend over time, sales distribution by category, and a geographic sales footprint map alongside core KPI cards (Revenue, Net Profit, Quantity Sold, Net Profit Margin).

---

## 👨‍💻 About Me
I am a Junior Reporting Analyst pursuing a Master of Information Technology (Business Intelligence & Data Analytics). My interests include Power BI, SQL, data visualization, and business reporting, and I use AI-assisted workflows as part of my day-to-day dashboard-building and DAX-authoring process.

---

## 🛠 Technical Skills

*   **Core BI & Modeling:** Microsoft Power BI (Desktop & Service), Power Query (M), DAX, Data Modeling
*   **Data Analytics & Infrastructure:** SQL, Microsoft Excel (Advanced), Data Cleaning & Validation
*   **Design & Methodology:** Dashboard & KPI Design, AI-Assisted Analytics Workflows

---

## 📫 Contact

*   **Email:** muhammadali.sajjad@gmail.com 
*   **LinkedIn:** [linkedin.com/in/mas-bi-da](https://linkedin.com/in/mas-bi-da) 
*   **GitHub:** [github.com/muhammadalisajjad-svg](https://github.com/muhammadalisajjad-svg)
