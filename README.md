# IPhone-Sales-Analysis

# Overview

This project focuses on analyzing iPhone sales data from Flipkart to extract insights into ratings, reviews, sale prices, and discount percentages. The analysis includes visualizations and statistical insights to understand customer preferences and market trends.

# Objectives

Identify the top 10 highest-rated iPhones sold in India.

Analyze the number of ratings and reviews for the highest-rated iPhones.

Examine the relationship between ratings, sale prices, and discount percentages.

# Project Structure

data/: Contains the apple_products.csv dataset used for analysis.

notebooks/: Jupyter notebooks for exploratory data analysis (EDA) and visualization.

scripts/: Python scripts implementing the analysis and visualizations.

results/: Generated visualizations and key insights.

README.md: Project overview and instructions.

# Dataset

The dataset includes the following columns:

Product Name: Name of the iPhone model.

Product URL: URL link to the product on Flipkart.

Brand: Product brand (Apple).

Sale Price: Sale price of the iPhone.

Mrp: Maximum retail price.

Discount Percentage: Discount offered on the sale price.

Number Of Ratings: Total number of ratings received by the product.

Number Of Reviews: Total number of reviews received by the product.

UPC: Unique product code.

Star Rating: Average star rating of the product.

Ram: RAM capacity of the iPhone.

# Key Steps

Step 1: Data Loading and Cleaning

Loaded the dataset using Pandas.

Verified that there are no missing values in the dataset.

Step 2: Data Analysis and Visualization

* Objective 1: Top 10 Highest-Rated iPhones

Identified the top 10 highest-rated iPhones based on the "Star Rating" column.

Displayed the product names of these iPhones.

* Objective 2: Number of Ratings and Reviews

Visualized the number of ratings for the highest-rated iPhones using a bar chart.

Visualized the number of reviews for the highest-rated iPhones using another bar chart.

* Objective 3: Analysis of Ratings and Sale Prices

Created scatter plots to examine:

The relationship between the number of ratings and the sale price.

The relationship between discount percentage and the number of ratings.

Included trendlines to highlight patterns.

# Key Tools & Libraries

Pandas: Data manipulation and preprocessing.

NumPy: Numerical computations.

Plotly: Interactive visualizations (bar charts and scatter plots).

# Results & Insights

The top 10 highest-rated iPhones include models like the iPhone 11 Pro Max and iPhone 12 series.

iPhones with higher ratings tend to have a higher number of ratings and reviews, indicating customer satisfaction and popularity.

Discount percentages correlate with the number of ratings, suggesting that discounts might attract more buyers.

# Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with suggestions or improvements.

# Contact

For questions or feedback, contact kulkarninikita32@gmail.com.

