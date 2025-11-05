# Cafe-Sales-Analysis
# ☕ Monday Café Sales Analysis (Power BI Dashboard)

**Power BI dashboard for café performance analysis and business insights.**

---

### 📸 Dashboard Preview
![Dashboard Preview](https://raw.githubusercontent.com/muhammad102331-hash/Cafe-Sales-Analysis/main/Cafe-Dashboard.png)

---

### 📊 Overview
This project presents an **interactive Power BI dashboard** built for **Monday Café**, helping analyze sales, profit, and category performance across multiple branches.  
It transforms raw data into actionable insights for informed business decisions.

---

### 🧩 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI Desktop (.pbix)** | Data modeling and visual dashboard design |
| **Microsoft Excel (.xlsx)** | Source dataset (sales, products, branches) |
| **Power Query Editor** | Data transformation and cleaning |
| **DAX (Data Analysis Expressions)** | KPI formulas and business metrics |

---

### 📁 Project Files
| File | Description |
|------|--------------|
| `Cafe Sales Analysis & Report.pbix` | Main Power BI dashboard |
| `monday_cafe_sales_2024_2025.xlsx` | Excel dataset |
| `Cafe-Dashboard.png` | Dashboard screenshot |

---

### 🧮 Sample DAX Measures
```DAX
Total Sales = SUM(Sales[Total Sales])
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE([Total Profit],[Total Sales])
Sales YTD = TOTALYTD([Total Sales],'Date'[Date])
