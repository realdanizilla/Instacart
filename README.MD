## Project Objective

The objective of this project is to analyze and clean data from Instacart, a grocery delivery platform similar to Uber Eats or iFood. The dataset provided has been modified to be smaller and includes missing and duplicate values for practice. The goal is to pre-process the data, perform exploratory analysis, and provide insights on customer purchasing habits.

## Project Structure

The project consists of the following steps:

1- Data Inspection and Understanding:

- Analyzed five datasets: instacart_orders.csv, products.csv, aisles.csv, departments.csv, and order_products.csv.
- Explored each dataset's structure and content to identify key variables and relationships.

2- Data Preprocessing:

  - Ensured appropriate data types for IDs and other fields.
  - Identified and handled missing values and duplicates to prepare clean data for analysis.
  - Documented assumptions and decisions made regarding data cleaning.

3- Exploratory Data Analysis (EDA):

  - Verified value ranges for variables such as order_hour_of_day and order_dow.
  - Created visualizations to display:
  - Number of orders by hour of the day.
  - Distribution of orders across days of the week.
  - Time intervals between repeat orders.
  - Analyzed specific distributions, such as order times on different days and customer order frequencies.
  - Identified top products and purchasing patterns, such as the most frequently bought items and items often included in repeated orders.



## Tools and Techniques

Tools and Techniques Utilized
Data Analysis & Visualization:

**Libraries**: Utilized Python libraries such as pandas for data manipulation and matplotlib/seaborn for visualizations.

**Exploratory Data Analysis (EDA):** Investigated data distributions and patterns to understand customer behavior on the Instacart platform.

## Data Cleaning & Preprocessing:

**Handling Missing Values**: Detected and managed missing entries.

**Removing Duplicates**: Identified and excluded duplicate records from the analysis.

**Data Transformation:** Adjusted data types and ensured consistent data for analysis.

## Results and Recommendations

**Customer Purchase Behavior:**

- High Repeat Purchase Rate: 58 customers exhibited a repeat purchase rate above 98%, indicating strong loyalty to specific products.
- Average Time Between Orders: Customers generally wait an average of 11 days between purchases. Most orders are made either every 30 days or weekly (every 7 days).
- Typical Order Size: The majority of customers purchase between 6 to 9 items per order, and they typically make between 1 and 5 orders overall.

**Top Products and Categories:**

Most Frequent First Items in Cart: The top items added to the cart first were:
- Bananas
- Bag of Organic Bananas
- Organic Whole Milk
- Organic Strawberries
- Organic Hass Avocado

**Top 20 Products Consistency:**

- The most purchased products, the most repeated products, and the first items added to carts are nearly identical. These products predominantly belong to categories like fruits, vegetables, and milk.
- Products with High Repeat Orders: There are 56 products where more than 90% of the orders are repeat purchases. - These products should always be in stock to avoid losing customers.

**Order Patterns and Trends:**

- Peak Ordering Times: The majority of orders are placed between 10 a.m. and 5 p.m., with peak hours being from 10 to 11 a.m. and again between 2 to 3 p.m.
- Day of Week Ordering Trends: Most orders are placed on Sundays and Mondays. There is an opportunity to boost sales on Wednesdays and Saturdays, particularly between 9 a.m. and 5 p.m.
- Repeat Purchase Trends by Customer: There is a segment of high-value customers with a repeat purchase rate above 90%, indicating these customers are vital for maintaining revenue stability.

**Marketing Insights and Opportunities:**

- Customer Retention Strategies: Customers who do not place an order by the 12th day since their last order could be targeted with marketing efforts to encourage repeat purchases.
- Focus on High Loyalty Products and Customers: Efforts should be concentrated on maintaining high stock levels for the top products that have high repeat purchase rates and engaging customers who consistently buy these items.

**Data Cleaning and Insights:**

- The data required preprocessing to handle missing values, particularly for products categorized in aisle 21 and department 100, which were missing labels.
- Removing duplicates and correcting data types were key steps in preparing the data for accurate analysis.

## Summary of Recommendations

- Target marketing on Sundays and Mondays, and increase efforts on quieter days (Wednesday and Saturday) to even out the sales distribution.
- Develop retention strategies for loyal customers, particularly those with repeat purchase rates over 90%.
- Ensure key products, especially those with high repeat purchase rates, are always in stock to prevent customer attrition.


## What I Have Learned From This Project

Through this project, I developed and honed the following skills and competencies:

- **Data Cleaning & Preparation:** Gained experience in handling missing data, correcting data types, and dealing with duplicates, all crucial steps in ensuring accurate analysis.
- **Data Analysis & Visualization:** Improved skills in creating meaningful visual representations of data and extracting insights from patterns and trends.
- **Customer Behavioral Insights:** Developed an understanding of how to use transactional data to derive insights into customer purchasing behaviors and trends
- **Effective Reporting:** Learned to document analytical steps and summarize findings clearly, ensuring that analysis is transparent and easy to understand.