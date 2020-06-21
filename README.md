# Directing-Customers-to-Subscription-Through-App-Behavior-Analysis
In this Machine Learning end to end project, we are working on financial application data and predict the customer who will take a premium version app subscription or not. Then the company will take action on the customers to give the offers or not. The data contain the customer’s behavior and our job to find the insights from it. To complete this project, we use python programming and it’s libraries **NumPy, Pandas, Matplotlib, and Seaborn.** 

## Bussines Problem  
The Financial Technology company (Fin-Tech Company) launch there mobile app. This app used for financial purposes like bank loans, savings, etc. in one place. It has two versions free and premium. The free version app contains basic features and customer wants to use the premium feature then they have to pay some amount to unlock it.  
The main goal of the company is to sell the premium version app with low advertisement cost but they don’t know how to do it. That’s a reason they are provided the premium feature in the free version app for 24 hours to collect the customer’s behavior. After that, the company hired the Machine Learning Engineer to find insight from the collected data (customer’s behavior).  
The job of the ML engineer is to find or predict new customer who is interested to buy the product or not. If the customers will buy a product anyway so no need to give an offer to that customer and loss the business. Only give offers to those customers who are interested to use premium version app but they can’t afford its cost. So the company will give offers to those customers and earn more money.  

## Know about dataset  
There are 50,000 users data with 12 different features. Let’s know each and every feature in brief.  
1. user: Unique ID for each user.  
2. first_open: Date (yy-mm-dd) and time (Hour:Minute:Seconds:Milliseconds) of login on app first time.  
3. dayofweek: On which day user logon.  
0: Sunday  
1: Monday  
2: Tuesday  
3: Wednesday  
4: Thursday  
5: Friday  
6: Saturday  
4. Hour: Time of a day in 24-hour format customer logon. It is correlated with dayofweek column.  
5. age: The age of the registered user.  
6. screen_list: The name of multiple screens seen by customers, which are separated by a comma.  
7. numscreens: The total number of screens seen by customers.  
8. minigame: Tha app contains small games related to finance. If the customer played mini-game then 1 otherwise 0.  
9. used_premium_feature: If the customer used the premium feature of the app then 1 otherwise 0.  
10. enrolled: If the user bought a premium feature app then 1 otherwise 0.  
11. enrolled_date: On the date (yy-mm-dd) and time (Hour:Minute:Seconds:Milliseconds) the user bought a premium features app.  
12. liked: The each screen of the app has a like button if the customer likes it then 1 otherwise 0.  
