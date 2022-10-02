# Credit Card Customer Segmentation

Objectives
The aim of this project is to derive customer segmentation of credit card for marketing strategy.

Dataset
The dataset used in this project is taken from https://www.kaggle.com/datasets/arjunbhasin2013/ccdata.

Executive Summary
1. Exploratory Data Analysis (EDA) and Data Pre-processing 
2. Machine Learning Model training 

Conclusion
By comparing the performance of three unsupervised learning models, we use KMeans clustering as the model as it has highest silhoutte score for clustering of 0.2% which means it has better data compact within its cluster and far from other clusters.

By using elbow method, we derived the optimal number of clusters for the data which is 4.

Upon analyzing the 4 different types of customer segmentation of the credit card customers, these are the characteristics of each customers:
- First group: These customers have lowest cash advance and balance amount left in their account. These are careful customers with their spending
- Second group: These customers have the highest purchases and one off purchase with highest purchases frequency. These customers are the most lucrative
- Third group: These customer don't make installment purchases abd lowest purchase frequency
- Forth group: These customers use cash advance often
