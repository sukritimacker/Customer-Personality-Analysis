# Grocery Insight Clustering for Customer Optimization

## Introduction
In this project, unsupervised clustering of data on the customer's records from a grocery firm's database was implemented. Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster. Customers were divided into segments to optimize the significance of each customer to the business and to modify products according to the distinct needs and behaviours of the customers. It also helps the business to cater to the concerns of different types of customers.

## About the dataset
The dataset consists of 2240 data points and 29 attributes. These attributes can be categorised in the following subsets:-

1. People
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise

2. Products
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years

3. Promotion
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

4. Place
- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to the company’s website in the last month

## Profiling the customers
1. Cluster 0
- Are definitely parents
- Have at least 2 members in the family, going up till 4
- Most have teenagers at home
- Relatively older

2. Cluster 1
- Are definitely not parents
- At max 2 members in the family
- There are more couples than singles
- A high-income group
- Spans mostly all ages

3. Cluster 2
- The majority of these people are parents
- Have at max 3 members in the family
- They mostly have one kid, and there are not many teenagers
- Relatively younger population

4. Cluster 3
- They too are definitely parents
- They have at least 2 family members with at max 5 members
- The majority of them have teenagers at home
- Relatively older
- A lower-income group
