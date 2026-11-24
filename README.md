Zomato Data Analysis Project

Exploratory Data Analysis using Python

1. Project Overview

This project explores Zomato restaurant data using Python to understand restaurant categories, customer ratings, voting patterns, online ordering availability, table booking, and approximate dining costs.

The objective is to identify patterns in restaurant data, answer business questions, and generate meaningful insights through Exploratory Data Analysis (EDA).

2. Project Objectives

Understand the structure and characteristics of the dataset.

Perform data cleaning and preprocessing.

Analyze restaurant categories and customer votes.

Explore restaurant ratings and customer preferences.

Compare online and offline ordering patterns.

Identify cost trends across restaurant categories.

Generate insights to support business understanding.

3. Tools and Technologies

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

4. Dataset Overview

The dataset contains 148 restaurant records and 7 columns.

Column

Description

Restaurant Name

Name of the restaurant

Online_Order

Online ordering availability

Book_Table

Table booking availability

Rate

Restaurant rating

Votes

Number of customer votes

Approx_Cost

Approximate cost for two people

Listed_In(Type)

Restaurant category

5. Data Cleaning

The following preprocessing operations were performed:

Converted restaurant ratings from text to numeric values.

Standardized column names to lowercase.

Renamed the approximate cost column.

Checked for missing values.

Checked for duplicate records.

The dataset contained no missing values or fully duplicated rows.

6. Exploratory Data Analysis

The project investigates the following 10 business questions:

How many customer votes has each restaurant type received?

How many restaurants offer table booking?

Which five restaurants have the highest number of votes?

Is there a relationship between restaurant ratings and customer votes?

What is the average rating for each restaurant type?

Which restaurant type is most common in the dataset?

What ratings do restaurants most commonly receive?

Which restaurant type has the highest average cost for two people?

Do restaurants offering online ordering have higher ratings?

Which restaurant types have more records without online ordering?

7. Key Findings

Dining represents 110 out of 148 restaurant records (74.3%).

Dining restaurants received the highest total votes (20,363).

Only 8 restaurants (5.4%) offer table booking.

Empire Restaurant received the highest votes (4,884).

Restaurant ratings and votes have a moderate positive correlation of approximately 0.49.

The Other category has the highest average rating (3.91).

The most common rating is 3.8.

Buffet restaurants have the highest average cost for two (671.43).

Restaurants offering online ordering have a higher average rating (3.86) than those without online ordering (3.49).

Dining has the highest number of records without online ordering (77).

8. Project Structure

Zomato-Data-Analysis/
│
├── data/
│   └── zomato_data.csv
│
├── notebooks/
│   └── zomato_EDA_project.ipynb
│
├── reports/
│   ├── Zomato_EDA_Project_Report.pdf
│   └── PPT.pptx
│
├── README.md
├── requirements.txt
└── .gitignore

9. Conclusion

The analysis identifies Dining as the largest restaurant category and the category with the highest total customer votes. Buffet restaurants have the highest average dining cost, while the Other category has the highest average rating.

Online-ordering availability is associated with higher ratings in this sample. These findings describe the 148 supplied records and should not be generalized to all Zomato restaurants.

Project Type: Exploratory Data Analysis (EDA)
Domain: Food & Restaurant Analytics
Language: Python