# Adidas Sales Data Analysis.


## Objective:
The purpose of this analysis is to discover relationships of various sales features with each other. This analysis will focus on cleaning and manipulating data in Jupyter notebook majorly using pandas library. And an interactive dashboard with three different views for "Sales Insights", "Product Insights" and "Customer Insights" will be created . 


## About Dataset:
The dataset used for the project is freely available on Kaggle. Thus, there wasn't a need to go through a thorough cleaning process. The columns in the dataset are, "Retailer", "Retailer ID", "Invoice Date", "Region", "State", "City", "Product", "Price per Unit", "Units Sold", "Total Sales", "Operating Profit", "Operating Margin", "Sales Method" and "Gender". The total number of rows in the dataset are 9648.


## Data Verification and Manipulation:


## Visualization:

Dashboard Link: https://public.tableau.com/app/profile/sandeep.patil6475/viz/DetailedDash/SalesDash

Home Dashboard:
![Home Dash](https://github.com/iamsandeeppatil3/adidas-sales-analysis/assets/60236271/231ffeac-25d6-4b2c-94d7-f030fe6cff49)

Three views for dashboard were created. 
1. Sales Insights:
a. Sales and Profits by States.
b. Sales and Profits by Time.
![Sales Dash](https://github.com/iamsandeeppatil3/adidas-sales-analysis/assets/60236271/fd55dd54-4c63-406d-8309-27706e744044)

2. Customers Insights:
a. Purchase Method Stats.
b. Purchase Methods by Time.
c. Average Product Prices by Purchase Methods.
![Customers Dash](https://github.com/iamsandeeppatil3/adidas-sales-analysis/assets/60236271/a0b059d1-f52a-409e-875f-8a5d48f00d3c)

3. Products Insights
a. Product Stats.
b. Product Sales by Time.
c. Product Sales by Region.
![Products Dash](https://github.com/iamsandeeppatil3/adidas-sales-analysis/assets/60236271/07fb9ad3-bb3f-49a0-b31e-43c1fb44b254)


## Findings and Conclusion:
Sales Insights:
1. It was found that New York State makes the highest sales as well as profits, with Nebraska State comimg at the last spot in both the categories.
2. There is an huge spike in sales and profits at the beginning of the year 2021, and the spike keeps rising throughout the year.

Products Insights:
1. Compared to the rise in sales of all the products in the beginning of 2021, 'Mens Street Footware' saw a highest rise.
2. Company sells most products in West region, and MidWest saw the lowest product sales.

Customers Insights:
1. Average price of all the product were cheapest when bought from 'Outlet', they are expensive when purchesed by the method 'InStore'.
2. At the beginning of 2021, sales by 'Online' method took a higher spike ccompared to the other two methods ie, 'Instore' and 'Outlet'. meanwhile, 'Instore' purchase decreased.
