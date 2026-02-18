# End-to-End-E-Commerce-Analytics-Pipeline
📌 Project Overview
This project builds a complete data analytics pipeline using the Brazilian E-Commerce Public Dataset by Olist (Kaggle). The goal is to transform raw transactional data into structured business insights by cleaning, merging, aggregating, and analyzing customer and order data. The pipeline covers data preparation, feature engineering, RFM analysis, clustering, visualization, and exporting cleaned datasets for further business intelligence or machine learning applications.

🎯 Objectives
- Analyze the Olist e-commerce dataset to:
  - Load and integrate multiple relational CSV files
  - Clean data (fix column names, parse dates, handle inconsistencies)
  - Merge product category translations
  - Build order-level and customer-level analytical datasets
  - Compute RFM (Recency, Frequency, Monetary) metrics
  - Assign R, F, M scores for customer segmentation
  - Apply KMeans clustering to group customers
  - Generate business-focused visualizations

📂 Dataset
Dataset Used: Brazilian E-Commerce Public Dataset by Olist (Kaggle)

- The dataset includes the following subdata sets:
  - Orders and order items
  - Customers and sellers
  - Products and product categories
  - Payments and reviews
  - Geolocation data

🛠 Tools and Libraries
 - Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

🔍 Methodology
1. Data Loading & Cleaning
  - Load multiple CSV files
  - Standardize column names
  - Parse date columns into datetime format
  - Handle missing values and inconsistencies

2. Data Integration
  - Merge product category name translations
  - Join orders, customers, payments, and products
  - Create unified analytical tables

3. Feature Engineering
  - Build order-level dataset
  - Build customer-level dataset
  - Compute RFM metrics
    - Recency: Days since last purchase
    - Frequency: Number of purchases
    - Monetary: Total revenue per customer
  - Assign R, F, M scores based on quantiles

4. Customer Segmentation
- Apply KMeans clustering on RFM features
- Create customer segments
- Interpret cluster characteristics

5. Visualization & Insights
- Top-selling products
- Revenue by region
- Monthly sales trends
- RFM score distributions
- Cluster heatmap for customer behavior analysis

6. Output & Export
- Save cleaned and transformed datasets
- Produce summary insights for reporting

💡 Insights & Business Value
- Identify high-value and loyal customers
- Detect at-risk or inactive customers
- Understand revenue concentration by region
- Track seasonal sales patterns
- Support data-driven marketing and retention strategies

⭐ Future Improvements
Deploy an interactive dashboard (Power BI / Streamlit / Tablua)
- Implement advanced clustering techniques
- Build customer lifetime value (CLV) models
- Develop churn prediction models
- Automate the pipeline for real-time analytics
