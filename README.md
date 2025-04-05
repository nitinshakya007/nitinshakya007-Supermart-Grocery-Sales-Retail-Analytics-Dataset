# Supermart-Grocery-Sales---Retail-Analytics-Dataset
# Project Overview
This project involves an in-depth analysis of the Supermart Grocery Sales dataset, which contains data on orders placed by customers on a grocery delivery application. The primary goal is to explore the data, uncover trends, and build a predictive model to forecast sales. The analysis focuses on understanding key sales drivers, profit margins, and the impact of discounts on customer behavior. The project also includes the development of a machine learning model to predict future sales.

# Dataset
The dataset includes 11 columns:

- Order ID: Unique identifier for each order.
- Customer Name: Name of the customer who placed the order.
- Category: Main category of the purchased product.
- Sub Category: Sub-category of the product.
- City: City where the order was delivered.
- Order Date: Date when the order was placed.
- Region: Region of the city.
- Sales: Total sales amount for the order.
- Discount: Discount applied on the order.
- Profit: Profit made from the order.
- State: State where the order was delivered.

# Project Objectives

# Data Cleaning and Preparation

- Convert date columns to datetime format.
- Handle missing values and duplicates.
- Extract and engineer features such as year and month from the date.

 # Exploratory Data Analysis (EDA)
 Analyze sales distribution across different categories and sub-categories.
- Identify the top-selling products and categories.
- Examine monthly and yearly sales trends.
- Explore the relationship between profit and discount.

# Data Visualization
- Create visualizations to highlight key insights.
- Plot sales trends over time and across different categories.
- Visualize profit margins and discounts.

  ![output_18_1](https://github.com/user-attachments/assets/0a802344-1132-4293-9147-3cf4b07f4ca1)
![output_19_0](https://github.com/user-attachments/assets/22990f1b-03e6-4311-9dfb-ba4177294f83)
![output_20_0](https://github.com/user-attachments/assets/5a84cee0-31df-4d49-90d8-2c62cc4f8c94)
![output_21_0](https://github.com/user-attachments/assets/9453e34c-d025-4dc2-a4a0-43d03f117a79)


# Predictive Modeling
- Build a linear regression model to predict sales based on features such as category, sub-category, city, region, state, discount, month, and year.
- Evaluate model performance using metrics like Mean Squared Error (MSE) and R-squared.

# Future Sales Forecasting
- Implement a time series forecasting model using ARIMA to predict future sales trends.
- Evaluate the forecasting model's accuracy and provide actionable insights for business decision-making.

# Tools Used:

- Python: Data manipulation, analysis, and visualization.
- Pandas & NumPy: Data processing and feature engineering.
- Matplotlib & Seaborn: Data visualization.
- Scikit-Learn: Machine learning model building and evaluation.
  

# Results

# Key Findings
- The top-performing categories are 'Eggs, Meat & Fish', 'Snacks', and 'Fruits & Veggies'.
- Sales have shown consistent growth over the years, with a significant increase in 2018.
- The correlation between profit and discount is minimal, suggesting that discounts do not significantly impact profit margins.

# Model Performance
- The linear regression model achieved an R-squared value of -0.0024240538359081576, indicating the proportion of variance explained by the model.

# Conclusion
This project provides a comprehensive analysis of grocery sales data, highlighting the key drivers of sales and profit. The predictive model and sales forecasting insights can help businesses make informed decisions regarding inventory management, marketing strategies, and pricing policies.
