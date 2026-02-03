# Blinkit-Sales-Performance-Analysis

This repository contains a comprehensive data analysis of Blinkit's sales performance using Python. The project focuses on uncovering key business insights regarding sales trends, product performance, and outlet efficiency.

## 🚀 Project Overview
The objective of this analysis is to evaluate various factors influencing sales at Blinkit. By processing and visualizing the data, we aim to identify patterns related to:
* **KPI Tracking:** Total Sales, Average Sales, Item Counts, and Ratings.
* **Product Attributes:** Impact of Fat Content and Item Categories on revenue.
* **Outlet Performance:** Analyzing sales across different outlet sizes, types, and geographic locations.
* **Growth Trends:** Evaluating sales performance based on the establishment year of the outlets.

## 📁 Dataset
The dataset `blinkit_data.csv` includes the following features:
- **Item Info:** Fat Content, Identifier, Type (Fruits, Snacks, etc.), Visibility, and Weight.
- **Outlet Info:** Establishment Year, Identifier, Size (Small/Medium/High), Location Tier, and Type.
- **Performance:** Sales and Customer Ratings.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - `Pandas`: Data manipulation and cleaning.
  - `NumPy`: Mathematical operations.
  - `Matplotlib` & `Seaborn`: Data visualization and charting.

## 📈 Key Analysis Features
The Python script (`Blinkit Analysis in Python.py`) performs the following:
1.  **Data Cleaning:** Standardizes "Item Fat Content" labels (e.g., mapping 'LF' and 'low fat' to 'Low Fat').
2.  **Sales by Fat Content:** Comparison of sales between Low Fat and Regular products.
3.  **Item Type Analysis:** Bar charts identifying the most popular product categories.
4.  **Outlet Establishment Trend:** Line chart showing sales growth based on the year outlets were founded.
5.  **Outlet Size & Location:** Breakdown of revenue by outlet size (Pie Chart) and Location Tiers (Bar Chart).
