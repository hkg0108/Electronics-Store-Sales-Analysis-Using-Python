# Electronics-Store-Sales-Analysis-Using-Python
Data Analysis


# Project Overview
This project leverages Python Pandas and Matplotlib to analyze 12 months' worth of sales data for an electronics store. The data consists of hundreds of thousands of purchase records, including details such as product type, purchase date, customer address, and costs. By cleaning the data and performing exploratory data analysis (EDA), this project aims to answer key business questions that can help optimize sales strategies.

# Data Cleaning & Preparation
The first step in the project involved cleaning and preparing the dataset for analysis. The following tasks were completed during this stage:

Dropped NaN values to ensure the dataset was clean.
Removed unnecessary rows based on specific conditions.
Changed data types (e.g., to_numeric, to_datetime, and astype) for better analysis and efficiency.

# Business Questions Answered
To provide actionable insights, the project focuses on answering five key business questions:

**What was the best month for sales?**
Identified the month with the highest revenue and the earnings generated.

**Which city sold the most products?**
Analyzed the sales data across cities to find the location with the highest product sales.

**What is the optimal time to display advertisements?**
Determined the time of day when customers are most likely to make a purchase, helping to maximize ad effectiveness.

**Which products are often sold together?**
Identified patterns in products commonly purchased together.

**Which product sold the most, and why?**
Analyzed the best-selling product and explored possible reasons for its popularity (e.g., pricing, demand, etc.).

# Tools and Techniques
The project makes use of several pandas and matplotlib methods to conduct the analysis:

**Data Concatenation:** Combined multiple CSV files into a single DataFrame using pd.concat.

**Data Manipulation:** Added new columns, parsed string data, and used the .apply() method for custom calculations.

**Aggregation:** Utilized groupby() to perform aggregate analysis on the data.

**Data Visualization:** Created bar charts and line graphs to visualize trends and insights.

# Insights & Results
**Best Month for Sales:** Identified the month with the highest total sales.

**Top Performing City:** Discovered which city had the most sales.

**Optimal Ad Time:** Determined the time slots that maximize customer engagement and sales.

**Popular Product Combinations:** Found patterns in product combinations frequently bought together.

**Best Selling Product:** Analyzed why a particular product was the best seller.

# Conclusion
This analysis offers insights into customer behavior and sales trends, enabling businesses to make informed decisions about inventory management, marketing strategies, and sales optimization.
