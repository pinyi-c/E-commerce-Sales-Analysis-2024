# E-commerce Sales Analysis 2024 — Investigating the Decline in Summer Revenue

## Project Overview
This project uses Python-based data analysis to examine product performance across seasons and identify the key factors behind declining summer sales. It demonstrates my ability to clean and process real-world datasets, conduct statistical analysis, and extract actionable business insights.

## Key Features
- Seasonal sales analysis to identify high- and low-performing periods  
- Investigation into underperforming summer product categories  
- Technical stack:  
  - Data processing: **Pandas**, **NumPy**  
  - Visualization: **Matplotlib**, **Seaborn**  
  - Statistical tests: **t-test**, **chi-square tests**

## Dataset
- **Source:** Kaggle — *E-commerce Sales Data 2024*  
- **Main File:** `customer_details.csv`  
- **Fields include:**  
  - Customer attributes: gender, age  
  - Purchase information: product category, season, order amount, purchase frequency, rating  

## Key Insights

### Demographic Analysis
- Men under 30 were the primary buyers, especially for hoodies, sweaters, jackets, and shirts.  
- Young women showed lower purchase activity in many apparel categories.  
- Men aged 50–60 showed higher spending on sweaters and gloves, while women over 60 showed significantly lower spending in these categories.

### Summer Sales Decline
- Typical summer items such as skirts, T-shirts, and shirts performed unexpectedly poorly during the summer.  
- Winter items consistently underperformed in the summer season. Statistical testing confirmed significant seasonal differences in revenue.

### Customer Segmentation
Customers were categorized into low, medium, and high purchasing power groups based on purchase frequency.
- Low and high purchasing power groups were more influenced by seasonal changes and showed higher spending in fall and winter.  
- Medium purchasing power customers remained relatively stable across seasons, except for a dip in summer.

## Dataset Limitations
- Each entry represents a single purchase, limiting the ability to analyze basket behavior or customer retention.  
- Missing product-level metadata (e.g., inventory, size, variations) restricts forecasting and product optimization analysis.  
- Only male customers used coupons in this dataset, indicating potential data collection bias affecting discount-related insights.
