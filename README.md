# 📊 ERP Export Data Analysis Project

This is a simple **Data Analysis Project** for a fictional export company using MySQL and Python (with Pandas). It demonstrates how to analyze customer orders, sales performance, and inventory data to generate insights and a clean Excel report.

---

## 📁 Project Structure

erp-export-analysis/ ├── data_analysis.py # Main Python analysis script ├── erp_export_analysis.sql # SQL file to create & populate the database ├── output/ │ └── export_analysis_report.xlsx # Final Excel report (auto-generated)

---

## 🧰 Technologies Used

- **Python 3**
- **MySQL / phpMyAdmin**
- **Pandas**
- **OpenPyXL** (for Excel export)
- **Matplotlib / Seaborn** (for optional visualizations)
- **Google Looker Studio** (for dashboards)

---

## 🗂️ Features

- Loads data from MySQL tables: `customers`, `products`, `sales_orders`, `inventory`
- Merges and cleans the data
- Calculates:
  - Sales per customer
  - Monthly revenue
  - Top-selling products
  - Inventory turnover ratio
  - Low stock alerts
- Exports all analysis to a single **Excel report**
- Easy to connect to **Google Data Studio** for dashboards

---

## 🚀 How to Run

1. **Set up MySQL database** using `erp_export_analysis.sql`
2. **Install dependencies** in Python:
   ```bash
   pip install pandas mysql-connector-python openpyxl
Run the Python script:

bash
python data_analysis.py
✅ Your Excel report will be saved in the output/ folder

📊 Dashboard
You can import the data into Google Looker Studio (Data Studio) using:

Google Sheets (by uploading Excel)

MySQL direct connector
