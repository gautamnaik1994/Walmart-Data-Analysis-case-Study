# Walmart Case Study

By Gautam Naik (gautamnaik1994@gmail.com)  

**About Walmart**

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

  
**Business Problem**

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the 
customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending 
habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male 
and 50 million are female).

**Metric**

- We will use visualization of all variable with purchase amount to visually confirm our findings.
- Central Limit Theorem with bootstrapping will be used to estimate the confidence interval.
- Hypothesis testing will be done on Gender, Marital Status and Age using z test and t test to answer question about spending patterns

  
**Dataset**

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. 
The dataset has the following features:  

- User\_ID:User ID  
- Product\_ID:Product ID  
- Gender:Sex of User  
- Age:Age in bins  
- Occupation:Occupation(Masked)  
- City\_Category:Category of the City (A,B,C)  
- StayInCurrentCityYears:Number of years stay in current city  
- Marital\_Status: Marital Status  
- ProductCategory: Product Category (Masked)  
- Purchase:Purchase Amount  


