# Walmart_Sales-_Forecasting
General Objective: To analyze Walmart sales data, identifying top-performing products, sales trends, and customer behaviors to optimize sales strategies and improve business performance.

**APPROACH**

**1)** Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.

**a)** Build a database

**b)** Create table and insert the data.

**c)** Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.

**2)** Feature Engineering: This will help use generate some new columns from existing ones.

**a)** Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.

**b)** Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.

**c)** Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.

**3)** Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

**4)** Conclusion:
