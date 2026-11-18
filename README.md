
# Olist E-Commerce Sales Data Analysis

## WeIntern Data Science Internship – Week 1 | Task 2

### 1. Project Overview

This project focuses on analyzing the Brazilian Olist E-Commerce dataset to understand sales performance, customer purchasing behavior, product category performance, regional sales distribution, and payment patterns.

The objective is to calculate important business KPIs, identify sales trends, generate meaningful insights, and communicate findings through structured analytical reports.

### 2. Task Objectives

- Calculate total revenue from delivered orders.
- Identify the total number of delivered orders.
- Calculate Average Order Value (AOV).
- Calculate total items sold.
- Identify the top-selling product category.
- Identify the top revenue-generating product.
- Analyze monthly sales trends.
- Perform regional sales analysis.
- Understand customer purchase behavior.
- Analyze payment methods.
- Generate actionable business insights.

### 3. Dataset Description

The analysis uses the cleaned Brazilian Olist E-Commerce datasets:

- Customers
- Orders
- Order Items
- Products
- Payments
- Reviews
- Sellers
- Geolocation
- Product Category Translation

### 4. Analysis Methodology

1. Imported Python libraries.
2. Loaded the cleaned datasets.
3. Inspected dataset structures.
4. Merged relevant datasets using common identifiers.
5. Filtered delivered orders for sales KPI calculations.
6. Calculated revenue, orders, AOV, and items sold.
7. Analyzed product and category performance.
8. Examined monthly and regional sales trends.
9. Analyzed customer purchasing behavior.
10. Evaluated payment patterns.
11. Generated business insights.
12. Exported analytical reports.

### 5. Key Performance Indicators

The analysis calculates:

- Delivered Product Revenue
- Total Delivered Orders
- Average Order Value
- Total Items Sold
- Top-Selling Category
- Top Revenue-Generating Product

### 6. Analytical Reports

The notebook exports analytical reports such as:

- sales_kpi_summary.csv
- monthly_sales_trend.csv
- category_revenue.csv
- state_sales.csv
- customer_purchase_analysis.csv
- payment_analysis.csv
- business_insights.csv

### 7. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### 8. Project Structure

```text
Task-2_Sales-Analysis/
│
├── data/
│   └── cleaned/
│
├── notebook/
│   └── task2_sales_analysis.ipynb
│
├── outputs/
│   └── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

### 9. How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_TASK2_GITHUB_REPOSITORY_URL
```

**Step 2:** Navigate to the project folder.

```bash
cd Task-2_Sales-Analysis
```

**Step 3:** Install dependencies.

```bash
pip install -r requirements.txt
```

**Step 4:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open and execute:

`notebook/task2_sales_analysis.ipynb`

### 10. Important Analytical Notes

- Sales KPIs are calculated using delivered orders.
- Delivered Product Revenue is based on product prices and excludes freight charges.
- AOV is calculated as delivered product revenue divided by distinct delivered orders.
- Each order-item row represents an item record; order_item_id is not a quantity field.
- Payment analysis uses the payment records available in the dataset and should be interpreted separately from delivered-order revenue.

### 11. Author

**Gaurav Varat**

WeIntern Data Science Internship – Week 1

### 12. Conclusion

This project demonstrates practical skills in data analysis, KPI calculation, data merging, exploratory analysis, customer behavior analysis, and business insight generation using Python.
