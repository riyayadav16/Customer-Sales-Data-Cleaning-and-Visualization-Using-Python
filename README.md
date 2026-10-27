# Customer Sales Data Cleaning and Visualization Using Python

## 1. Project Overview

In this project, I worked with messy customer sales data. I used Python to clean the data and created five charts to understand customer spending patterns.

This project helped me learn how to clean data, analyze information, and create visualizations.

## 2. Project Objectives

- Clean messy customer data using Pandas.
- Find and handle missing values and duplicate records.
- Understand customer spending patterns.
- Create five charts using Seaborn and Matplotlib.
- Learn how to find useful information from data.

## 3. Dataset Information

The dataset used in this project is `messy_customer_sales_data.csv`.

- Original dataset: 10,200 rows.
- Cleaned dataset: 8,996 rows and 12 columns.

The dataset includes customer details such as age, gender, city, signup date, purchase amount, and feedback score.

## 4. Tools and Libraries

- **Python:** Main programming language.
- **Pandas:** Used to clean and analyze data.
- **Seaborn:** Used to create charts.
- **Matplotlib:** Used to display and customize charts.
- **Google Colab:** Used to write and run Python code.

## 5. Data Cleaning

I used Pandas to inspect and clean the dataset.

The main steps included:

- Checking the dataset structure.
- Finding missing values.
- Checking duplicate records.
- Handling missing values.
- Reviewing unusual values.
- Preparing the data for visualization.

The cleaned data was stored in a DataFrame called `df_clean`.

## 6. Visualizations Created

### 1. Histogram: Purchase Amount Distribution

Shows how customer purchase amounts are spread across different ranges.

**Finding:** A large number of values appear around ₹24,000–₹25,000. This may be due to filling missing purchase amounts with the median.

### 2. Bar Plot: Average Purchase Amount by City

Compares the average purchase amount across cities.

**Finding:** Average spending is similar across cities, with Bangalore and Delhi slightly higher.

### 3. Scatter Plot: Age vs Purchase Amount

Shows the relationship between customer age and purchase amount.

**Finding:** No clear relationship between age and spending is visible. Some unusual age values also need checking.

### 4. Box Plot: Purchase Amount by Feedback Score

Compares purchase amounts for different customer feedback scores.

**Purpose:** Helps us compare typical spending and the spread of purchase amounts across feedback scores.

### 5. Heatmap: Correlation Between Numeric Columns

Shows relationships between age, purchase amount, and feedback score.

**Purpose:** Helps us understand whether these numerical values are related.

## 7. Key Learnings

Through this project, I learned how to:

- Clean data using Pandas.
- Handle missing values and check duplicates.
- Group data and calculate averages.
- Create five different visualizations.
- Understand customer spending patterns.
- Identify unusual values in a dataset.
- Explain findings using simple charts.

## 8. Challenges

Some challenges in this project were handling missing values, identifying unusual age values, and understanding how data cleaning can affect charts.

For example, filling missing purchase amounts with the median can create a visible spike in the histogram.

## 9. Future Improvements

In the future, I would like to:

- Improve the handling of missing values.
- Correct unusual age values.
- Create more visualizations.
- Explore customer spending over time.
- Perform more detailed data analysis.

## 10. Conclusion

This project gave me practical experience in data cleaning and visualization using Python.

I used Pandas to clean the data and Seaborn with Matplotlib to create five charts. These charts helped me explore customer spending, city-wise averages, age, feedback scores, and relationships between numerical values.

Overall, this project helped me understand the basics of data analysis and how to turn messy data into useful information.

## 11. Project Files

- `Cleaned_messy_sales_data.ipynb` — Contains the Python code, data cleaning steps, and visualizations.
- `messy_customer_sales_data.csv` — Original dataset.
- `README.md` — Project description and findings.

## Author

Created as a beginner project to practice Python, Pandas, Seaborn, Matplotlib, and data analysis.
