# Customer-Segmentation
- Description and Motivation This project analyzes the data from the customers of a retail company, and try to understand the behaviour of their customers. That can give the company a lot of insights on how to plan their next campaigns, who would be the target of a new product, what are the most important customers, etc.

Link to the original dataset: https://www.kaggle.com/imakash3011/customer-personality-analysis

- Main Steps

• Introduction

• Preprocessing: Feature Engineering, removing nulls, removing outliers, changing categorical features and removing irrelevants variables.

• Exploratory Data Analysis (EDA): Some plots to understand our features distribution, and how they relate to each other

• Clustering: Scaling the features, Principal components analysis (PCA) and K-Means

• Evaluation of the results: Who are the customers assigned to each customer?

CONCLUSIONS:
Conclusions¶
Cluster 1:
1. About 36% of customers
2. High Income Group
3. Almost all have 0 or 1 children
4. spend a lot of money overall
5. Make Fewer purchases, but high in value
6. Not sensitive to discounts
7. Buy Fewer essential items
Cluster 2:
1. Largest group (about 44%)
2. Medium to high income
3. Spend the most overall
4. Make the most purchases
5. Not sensitive to discounts
6. % of essentials purchased is around average
Cluster 3:
1. Smallest group (about 20%)
2. Low to medium income
3. Everyone has at least 1 child
4. Highly sensitive to discounts
5. Mostly buy non-essential items (like wine and gold)
6. Spend a moderate amount
7. Make a moderate number of purchases
Therefore, it would be a good idea to focus special discount offers on customers in Cluster 3. On the other hand, customers in Cluster 1 are not very responsive to discounts, so marketing efforts involving discounts might not be effective for them.











- Files in the repository:

• marketing_campaign.csv: A dataset with 2040 rows, and each one of them stores information about a specific customer. • customer_segmentation.ipynb: The notebook of the project • customer_segmentation.py. The project as a python file.

- Libraries used: Pandas, Numpy, Datetime, Seaborn, Matplotlib, Sklearn
