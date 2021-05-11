# Unsupervised-Machine-Learning-for-Customer-Segmentation
Bank data analytics for different kind of customers to show targeted ADs

# Overview
To identify similar bank customers using the bank data.The dataset consists of the creditcard details of each customers.
Some of the features are transaction frequency, amount, tenure etc.
[The dataset can be downloaded from this link ](https://www.kaggle.com/arjunbhasin2013/ccdata)

# Objective
Here we have divided the customer into 6 different clusters.The customers in each cluster are similar to the custors in that cluster they belong to.
We have used the [k-means algorithm](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) to seperate the customers to different clusters.
All the data Vizualization tasks has been performed to get the insights from the data.The optimal number of clusters has been decided by using the elbow metod.
Further [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) has been applied to perform dimentionality reduction.
