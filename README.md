# Coffee-Sales-Dashboard-Using-Excel
## OVERVIEW
Using Excel for analyzing a coffee shop's sales data.  The goal is to gain insights that will help enhance business performance by examining factors like what individuals buy, when they buy it, and how busy the stores are.  We'll use Excel to examine trends like peak sales hours, popular products, and how sales change between days, months, and store locations after cleaning and organizing the data.
## PROBLEM STATEMENT
Analyze sales data and use Excel to create a coffee shop dashboard.  Find patterns, trends, and insights that may help guide strategic choices and improve company performance.  The goal is to investigate many facets of sales data, including as revenue patterns, peak sales times, and product performance, in order to find practical insights that help enhance sales strategies.
## Tools
Microsoft Excel
## RECOMMENDED ANALYSIS
- How do sales vary by day of the week and hour of the day ?
- Are there any peak times for sales activity ?
- What is the total sales revenue for each month ?
- How do sales vary across different store locations ?
- What is the Average Price Per Order ?
- Which products are the best selling in terms of Quantity & Revenue ?
- How do sales vary by Product Category and Size ?
## DATA PREPARATION
During the data preparation phase, the coffee shop's raw sales data—including transaction logs and product details—will be gathered and arranged in a structured manner that can be examined in Excel.  This entails standardizing formats, guaranteeing data integrity, and cleaning the data to get rid of any mistakes, missing numbers, or inconsistencies.  To aid in analysis, data is also combined and converted as necessary. Examples of this include figuring the average order value, average bill per person, and total sales.  The prepared data will be used as the basis for creating the dashboard after it has been cleaned and organized.
### DATA CLEANING AND TRANSFORMATION
**In Power query editor**
- Going over each column to gain a solid understanding of the data and its domain context.  This aids in identifying mistakes, discrepancies, and crucial data pertaining to the coffee shop's operations.  
- In the "product_detail" column, abbreviations like "Lg," "Rg," and "Sm" were used to indicate the size of items.  However, in order to give a more accurate picture of product sizes, a new column called "size" was added.  Rg >> Regular, Lg >> Large, Sm >> Small.
- To improve the dataset's homogeneity and cleanliness, leading and trailing spaces were removed from every column.
- Date values were eliminated from the "transaction_time" column during a refining process, leaving just the time in the format HH:MM:SS.
- "Total_bill" was a new custom column that was formed by multiplying "unit_price" and "transaction_qty" for every item.  A thorough summary of the total sales made from every transaction is given by this feature.
-  A thorough examination of how sales vary on various days and months is made possible by extracting the "day of the week" and "month name" from the "transaction_date" column.  Similarly, peak sales hours may be identified by extracting the "hour of the day" from the "transaction_time" column.
 ## PIVOT TABLES
Quickly summarized and analyzed data using pivot charts, allowing for the quick discovery of trends and patterns.  Additionally, creating dynamic dashboards is made easy by utilizing pivot charts.
#### Snapshot
![Image](https://github.com/user-attachments/assets/22864965-f288-4e8d-baa6-35b26269b804)
## DASHBOARD OVERVIEW
Created an appealing and dynamic dashboard for coffee sales analysis.  This interactive platform provides stakeholders with a simple interface for easily exploring key data, trends, and insights.
- Line charts were used to depict sales patterns over the course of the day, highlighting peak sales times and indicating changes in client demand.
- Used horizontal bar charts to represent daily sales performance, allowing for easy comparison of sales numbers across different days of the week.
- Used pie charts and donut charts to show the percentage distribution of sales depending on product sizes and categories, offering a clear visual picture of each size and category's contribution to total sales.
- Implemented column charts to present footfall and sales statistics for each retail location, permitting comparison of consumer traffic and income production across multiple locations.
#### Snapshot
![Image](https://github.com/user-attachments/assets/09c5ea11-2f01-4255-9966-a7f1955ba87b)
### INSIGHTS
### Busiest Days and Times
- The busiest hours for coffee sales are between 8:00 AM and 10:00 AM, indicating strong demand during morning rush hours.
- Mondays and Fridays tend to have the highest sales volumes, indicating increased demand at the beginning and end of the workweek.
### Top Products
- Barista Espresso emerges as the best-selling product,followed by Brewed Chai Tea ranks as the second-highest selling product.
### Percentage share based on Size
- Large-sized drinks dominate the sales representing the preferred choice among customers while Small-sized drinks are the least contributed.
### Percentage share based on Category
- Coffee and Tea Categories account for the largest percentage share of sales which is about 67% with Coffee being the most contributed(39%).
### Comparable Footfall Distribution
- All stores exhibit almost similar level of footfall throughout the months, indicating a balanced distribution of customers across different locations.
## REFERENCE
https://youtu.be/Rthh_bK5xUs?si=xH9OFkFlddvLfi5e
