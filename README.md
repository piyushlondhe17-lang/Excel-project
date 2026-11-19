# Excel-project
# 🛒 Supermarket Sales Dashboard (Excel)

An interactive Excel dashboard that analyses supermarket sales data across branches, cities, product lines, customer types, payment methods and time of day. Built with pivot tables, pivot charts, formula-driven charts and slicers.



## 📌 Overview

The workbook takes 1,000 raw sales transactions (January–March 2019), cleans them, adds calculated columns, and presents the results on a single dashboard that can be filtered with slicers.

## 📂 Workbook structure

| Sheet | Purpose |
|---|---|
| **Real Data** | Original raw transaction data |
| **Clean Data** | Cleaned table with added columns (month, hour, time of day, day of week, revenue, profit, etc.) |
| **Pivot Table** | Pivot tables that feed the dashboard charts and KPI cards |
| **Dashboard** | Final interactive dashboard with KPI cards, charts and slicers |
| **Chart Data** | Formula-driven helper tables (`SUMIFS` / `AVERAGEIFS`) for the extra charts |

## 📊 Dashboard contents

**KPI cards**
- Total Order Value
- Total Sales
- Total Revenue
- Total Profit
- Min Sale
- Max Sale
- Profit Margin

**Charts**
- Revenue by product line
- Sales by city
- Peak hours (orders by day of week and time of day)
- Monthly sales trend by branch
- Customer membership breakdown (gender × customer type)
- Sales by payment method
- Sales by day of week
- Gross income by product line
- Monthly sales trend
- Average rating by branch

**Slicers**
City · Product line · Gender · Month · Customer type · Payment · Branch · Time of day · Day of week

> The pivot charts respond to the slicers. The four charts under *Additional Insights* are formula-based and do not.

## 🎨 Design

- Header colour `#0F172A` (dark navy) with a blue palette (`#1E3A8A`, `#2563EB`, `#60A5FA`, `#93C5FD`) used across all charts
- Soft slate background (`#EEF2F7`) with white chart cards
- Custom slicer style (**DashNavy**) matching the dashboard theme

## 🛠️ Tools and techniques

- Microsoft Excel (desktop)
- Pivot tables and pivot charts
- Slicers
- Formulas: `SUMIFS`, `AVERAGEIFS`, `GETPIVOTDATA`, `TEXT`
- Linked text boxes for KPI cards

## ▶️ How to use

1. Download `Super_Store_Dashboard_Updated.xlsx`.
2. Open it in **Microsoft Excel (desktop)**. Slicers and pivot charts are not fully supported in Excel Online, Google Sheets or LibreOffice.
3. Go to the **Dashboard** sheet and click the slicers to filter the data.
4. If you change the source data, use **Data → Refresh All**.

## 📝 Notes

- The *Profit Margin* card is calculated as profit ÷ sales from the pivot data; check the definition if you reuse it for reporting.
- KPI cards are linked to cells on the **Pivot Table** sheet.

## 👤 Author

**Your Name**
[LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
