# Superstore Data Analysis

**Google Colab Project:** https://colab.research.google.com/drive/1TTPpaI3pOpK1ccdMzjNzoLHlcdxKhwun#scrollTo=MyZQcUnGQ41I

## Project Overview

This project analyzes the Kaggle Superstore dataset to uncover key insights into sales, profitability, customer segments, regional performance, and product trends.

Data cleaning and preprocessing were performed using Python to ensure data accuracy and consistency. Exploratory Data Analysis (EDA) was then conducted to identify patterns across regions, categories, products, customers, and time periods.

The project also includes visualizations and a machine learning model to support data-driven analysis and business decision-making.

## Key Analysis Areas

* Overall sales and profit performance
* Regional sales and profitability
* Profitability by product category and sub-category
* Impact of discounts on profit
* Customer segment performance
* Monthly and yearly sales trends
* Shipping mode usage
* Average profit per order
* Underperforming states and cities
* Relationship between quantity sold and profit
* Top profit-making and loss-making products
* Monthly profit prediction using Robust Linear Regression

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

## Machine Learning

A Robust Linear Regression model using RANSAC was developed to predict monthly profit by product category.

The model achieved an **R² of approximately 0.503**, with an **RMSE of approximately $4,483.66** and an average **log-scale prediction error of 32.2%**.

The model was used as a decision-support tool to identify relationships between sales, quantity, discounts, product categories, and profitability.

## Repository Contents

* `superstore_analysis.ipynb` — Complete Python analysis, visualizations, and machine learning model
* `Sample - Superstore.csv` — Dataset used for the analysis
* `README.md` — Project documentation

## Key Findings

* The **West and East regions** generated the highest sales, each reaching approximately $700,000.
* **Technology** was the most profitable category, followed by **Office Supplies**.
* Several sub-categories and products generated negative profits and require further investigation.
* Sales were generally stronger during the second half of the year, particularly from **August to December**.
* The **Canon imageCLASS 2200 Advanced Copier** was among the most profitable products.
* Some products, including certain 3D printers and tables, generated significant losses.
* Higher quantities did not necessarily guarantee higher profits, highlighting the influence of pricing, discounts, and product characteristics.

## Business Recommendations

* Prioritize high-profit categories and products.
* Focus resources on strong-performing regions while investigating weaker areas.
* Optimize discount strategies to protect profit margins.
* Review, reprice, or reconsider consistently loss-making products.
* Align inventory and marketing strategies with seasonal demand.
* Use machine learning predictions as decision-support rather than as a replacement for business judgment.
