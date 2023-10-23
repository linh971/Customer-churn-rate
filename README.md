# Customer churn rate
## 1. Introduction
### 1.1. Background
For this project, Let's look at the data of a multinational bank ABC. The mission is to discover important information about customer churn rates so that the bank can improve and classify customers into different types to reach them appropriately with different strategies.

This data bag includes more than 10,000 customer information records, including 12 corresponding variables:

customer_id: Customer code
credit_score: Credit score
country: Country
gender: Gender
age: Age
tenure: Term of office
balance: Remaining money
products_number: number of services used
credit_card: Credit card
active_member: Active member
estimated_salary: Estimated salary
churn: used as the target. 1 if the customer has left the bank during some period or 0 if he/she has not.
### 1.2. Objectives
This visualization study will focus on data exploration and draw key insights:
-  Exploratory Data Analysis (EDA)
-  RFM analysis: understand your customer's RFM features (Recency, Frequency, Currency)
-  Classify customers based on their information RFM: Clustering model, LogisticRegression, RandomForest, tree, GaussianNB
### 1.3. Tool used
Python:
-  Data cleaning and preparation
-  Exploratory Descriptive Analysis (EDA)
-  Recency-Frequency-Monetary (RFM) Analysis
-  Clustering models: LogisticRegression, RandomForest, tree, GaussianNB
## 2. Result
### 2.1. Analysis
#### 2.1.1. Customers
  Service users (mostly French) account for the majority of sales and this will be the bank's main customer base to carry out more campaigns. 
  However, Germany and Spain have an equal number of customers. But the abandonment rate of Spain and Germany is higher than France, especially Germany is nearly twice as high (> 30%). It is necessary to find out the cause so that the bank can fix this error.
#### 2.1.2. Churn rate
  Customer age is unevenly distributed, focusing mainly on people over the age of 20, the majority of customers aged 51 - 60 have a high churn rate (over 50%), customers in the remaining age groups have left at a rate of about 10%, especially groups of customers between the ages of 41-50 and 61-70 have a churn rate of about 35%.
  Customers using 1 service account for more than 50% and using 2 services is 45.9% and the remaining customers use 3.4 services. In general, customers who use 1 to 3 services have a fairly low churn rate, but customers who use 3 or 4 services leave a lot (3 services >80%, 4 services 100%).
  Customers using credit cards account for (70.6%) However, the churn rate for customers using credit cards and not using credit cards is the same (approximately 20%).
  Customers who actively use banking services and customers who do not use them regularly have similar numbers Customers who do not regularly use banking services have a higher churn rate, but this is quite understandable.
### 2.2. Learning model


