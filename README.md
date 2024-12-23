# Global Superstore Analysis

### Project Overview 
Global Superstore is a global online retailer based in New York, boasting a broad product catalog and aiming to be a one-stop-shop for its customers. Global The superstore’s clientele, hailing from 147 different countries, can browse through an endless offering with more than 10,000 products. This large selection comprises three main categories: office supplies (e.g., staples), furniture (e.g., chairs), and technology (e.g., smartphones).
The goal of this analysis is to analyze and draw out meaningful insight from the Superstore dataset which would aid management in making informed decisions to improve performance and profitability.

### Data Source
The data set was provided by Digitaley drive and it had 3 tables
- Order: This contains details about individual orders,including product details, customer info and sale metrics. 51290 rows and 24columns
- Returns: Records number of returned orders. 1000 rows and 3 columns
- People: Contains details of regional managers overseeing sales and operations.13 rows and 2 columns

### Tools
- Power Query
- Dax
- Power BI

  ### Data cleaning and transformation
Loaded the dataset into power query in Power BI the dataset was mostly clean, Made changes in the returns and order table by making the first row headers. Afte rwhich I loaded the tables into power bi.

### DATA MODELING
I created a calendar table using DAX function CALENDARAUTO()
A relationship had already been created between Orders table and people, I created another relationship between the calendar table and the order table, the People table and the returns table.

### Exploratory Data analysis
EDA involved exploring the survey data to answer key questions like
Question 1.
a) What are the three countries that generated the highest total profit for Global Superstore in 2014? b) For each of these three countries, find the three products with the highest total profit. Specifically, what are the products’ names and the total profit for each product?
Question 2.
a) Identify the 3 subcategories with the highest average shipping cost in the United States.
Question 3.
a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries?
b) What factors might be responsible for Nigeria’s poor performance? You might want to investigate shipping costs and the average discount as potential root causes.
Question 4.
a) Identify the product subcategory that is the least profitable in Southeast Asia. Note: For this question, assume that Southeast Asia comprises Cambodia, Indonesia, Malaysia, Myanmar (Burma), the Philippines, Singapore, Thailand, and Vietnam.
b) Is there a specific country i n Southeast Asia where Global Superstore should stop offering the subcategory identified in 4a?
Question 5.
a) Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average profit so low?
Question 6.
a) Which product subcategory has the highest average profit in Australia?
Question 7.
a) Who are the most valuable customers and what do they purchase?

### Data Analysis 
~DAX




### Dashboard 
