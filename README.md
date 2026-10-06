# Sales Performance Analysis

## 📌 Project Overview

This project analyzes retail sales data to understand overall sales performance across regions, product categories, individual products, and months. It was completed during my Data Analytics Internship at Alfido Tech through InternSpark.

The objective was to clean the data, calculate key business KPIs, and uncover insights that can help improve sales strategy, marketing focus, and inventory planning.

---

## 🎯 Problem Statement

The business wants to know:

- How much revenue is generated, and how many orders are placed?
- Which regions and product categories drive the most sales?
- Which individual products are the biggest revenue drivers?
- How do sales change across months, and are there seasonal patterns?
- Where are the opportunities to improve sales performance?

---

## 📊 Dataset

A retail (Superstore-style) sales dataset of US orders, with details of orders, customers, products, locations, and sales.

**Dataset Size:** 9,800 rows × 18 columns

**Key columns:** Order_ID, Order_Date, Ship_Mode, Customer_ID, Segment, State, Region, Category, Sub_Category, Product_Name, Sales

**Note:** the dataset has no profit or website-traffic data, so profit margin and conversion metrics could not be calculated.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Loading & Exploration
- Loaded the dataset and checked its structure with `head()`, `info()`, `shape`, and `describe()`

### 2. Data Cleaning
- Checked for missing values: only `Postal_Code` had 11 missing values
- Checked for duplicate records: none were found
- Converted `Order_Date` to datetime format
- Created `Year` and `Month` columns for time-based analysis

### 3. KPI Calculation
- Total Revenue
- Total Orders
- Average Order Value (AOV)

### 4. Exploratory Data Analysis & Visualization
- Sales by Region
- Sales by Category
- Top 10 Products by sales
- Monthly Sales Trend

---

## 📈 Key Findings

**KPIs**

| KPI | Value |
|---|---|
| Total Revenue | $2,261,536.78 |
| Total Orders | 4,922 |
| Average Order Value | $459.48 |

**Insights**

- **Regions:** West (about $710K) and East (about $670K) bring in the most sales, together roughly 60% of revenue. South is the weakest region (about $390K).
- **Categories:** Technology leads with about $830K (roughly 37% of sales), followed by Furniture (about $730K) and Office Supplies (about $705K).
- **Products:** Canon imageCLASS 2200 Advanced Copier is the top product with about $61K in sales, more than double the next product. The top 10 products together bring in around 11% of total revenue, so sales are spread across many products.
- **Seasonality:** Sales peak around the end of the year, with November (about $350K), December (about $320K), and September (about $300K) as the strongest months. February (about $59K) and January (about $94K) are the weakest.
- **Order value:** The median sale is $54 while the maximum is $22,638, so the business has many small orders and a few very high-value ones.

---

## 💡 Business Recommendations

- Increase marketing investment in Technology and in top-selling products.
- Build region-specific campaigns for South and Central, which lag behind West and East.
- Plan inventory and promotions around the Sept–Dec peak, and run offers in the slow months of January and February.
- Run promotions or review the range for low-selling products.
- Use bundle offers and cross-selling to raise the Average Order Value.
- Collect profit data in future so that margin and profitability can be analyzed.

---

## 📁 Files

- `Sales_Performance_Analysis.ipynb` – Complete analysis notebook
- `README.md` – Project documentation

---

## 👩‍💻 Author

**Vaishnavi Tiwari**

B.Tech – Computer Science & Artificial Intelligence | Aspiring Data Analyst

- GitHub: [vaishnavitiwari1109](https://github.com/vaishnavitiwari1109)
