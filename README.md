[README (1).md](https://github.com/user-attachments/files/32463933/README.1.md)
# sales-analysis-excel-project
A simple, formula-driven sales analysis workbook built in Excel — includes raw data, automated summary calculations, and an interactive dashboard with charts and KPIs.
# 📊 Sales Analysis Excel Project

A simple, formula-driven sales analysis workbook built in Excel — includes raw data, automated summary calculations, and an interactive dashboard with charts and KPIs.

## 📁 Project Structure

The workbook (`sales_analysis_project.xlsx`) contains 3 sheets:

| Sheet | Description |
|---|---|
| **Raw Data** | 150 sample sales records (Order ID, Date, Region, Product, Category, Units Sold, Unit Price, Revenue) |
| **Summary** | Auto-calculated totals by Region and Category, plus key business metrics |
| **Dashboard** | Visual overview with bar chart, pie chart, and KPI cards |

## 🛠️ Features

- **Formula-driven**, not hardcoded — all totals recalculate automatically when raw data changes
- **`SUMIFS`** used to aggregate revenue and units by Region and Category
- **`COUNTIF`** / **`COUNTA`** used for order counts
- **Key Metrics**: Total Revenue, Total Units Sold, Total Orders, Average Order Value
- **Charts**: Bar chart (Revenue by Region), Pie chart (Revenue Share by Category)
- **Dashboard KPI cards** linked live to the Summary sheet

## 📈 Skills Demonstrated

- Excel formulas (`SUMIFS`, `COUNTIF`, `COUNTA`, cross-sheet references)
- Data aggregation and summarization
- Chart creation (Bar & Pie)
- Dashboard design and KPI reporting
- Structured, multi-sheet workbook design

## 🚀 How to Use

1. Download `sales_analysis_project.xlsx`
2. Open in Excel, LibreOffice Calc, or Google Sheets
3. Edit any row in **Raw Data** (e.g., change Units Sold or Unit Price)
4. Watch the **Summary** and **Dashboard** sheets update automatically

## 📌 Notes

- Sample data is randomly generated for demonstration purposes
- Built using Python (`openpyxl`) to programmatically generate the workbook with live formulas

---
*Feel free to fork this project and adapt it with your own dataset!*
