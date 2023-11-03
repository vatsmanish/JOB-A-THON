# This repository contains solution of a JOB A THON cunducted by Analytics Vidhya(https://datahack.analyticsvidhya.com/contest/job-a-thon-january-2023/#About)

#### Problem Statement
VahanBima is one of the leading insurance companies in India. It provides motor vehicle insurances 
at best prices with 24/7 claim settlement. It offers different types of policies for both personal and 
commercial vehicles. It has established its brand across different regions in India.
Around 90% of the businesses today use personalized services. The company wants to launch 
different personalized experience programs for customers of VahanBima. The personalized 
experience can be dedicated resources for claim settlement, different kinds of services at doorstep, etc. 
Inorder to do so, they would like to segment the customers into different tiers based on their customer 
lifetime value (CLTV).
Inorder to do it, they would like to predict the customer lifetime value based on the activity and 
interaction of the customer with the platform. So, as a part of this challenge, your task at hand is to 
build a high performance and interpretable machine learning model to predict the CLTV based on the 
user and policy data.

Approach
• After importing data, I did some EDA (check null values, check distributions and skewness, 
checked unique values etc), I found that there was skewness in two numerical columns.

• Feature Engineering – I tried transforming numerical columns by grouping various cat columns 
and taking mean but did not gave me good score.
• I combined some categorical columns which gave me good score.
• Hyperparameter tunning – I tunned hyper parameters with the help of optuna.
• Used Random Forest importannce matrix to get the best hypermeter
