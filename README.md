# E-Commerce Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](Data-Source)
- [Recommendations](#Recommendations)

### Project Overview

This data analysis project aims to deliver insights into the sales performance of an e-commerce company over the past year. By examining different facets of the sales data, we intend to identify trends, offer data-driven recommendations, and gain a deeper understanding of the company's performance.


<img width="638" alt="Screenshot 2024-05-10 181100" src="https://github.com/kennyperez/Data-Analysis/assets/61357698/26bf9199-812c-4e70-a90f-530bd33d1e6c">

## Data Source

Sales Data: The primary dataset for this analysis is the "sales_data.csv" file, which contains detailed information about each sale made by the company.


### Tools

- Excel - Data Cleaning
   - [Download here](https://microsoft.com)
- SQL Server - Data Analysis
- PowerBI - Creating Reports

### Data Cleaning/preparation


In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.


### Exploratory Data Analysis


EDA involved exploring the sales data to answer key questions, such as:
what is the overall sales trend?
which products are top sellers?
What are the peak sales periods?

### Data Analysis


Include some interesting code/features worked with
Results

```sql
SELECT * FROM table1
WHERE cond = 2
```

### Results/Finding

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing

### Recommendations
   
Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers
effectively.

### Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a
few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue


### References

1. SQL for business analyst By Wetty
2. [Stack overflow](https://stackoverflow.com)



