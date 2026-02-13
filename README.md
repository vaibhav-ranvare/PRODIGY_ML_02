# PRODIGY_ML_02
Customer Segmentation using K-Means Clustering
This project applies K-Means Clustering, an unsupervised machine learning algorithm, to segment customers of a retail store based on their purchasing behavior.
The goal is to group customers into distinct clusters based on: Annual Income (k$) and Spending Score (1–100)
Customer segmentation helps businesses understand customer behavior and design targeted marketing strategies.
To identify meaningful customer groups using clustering techniques, enabling data-driven business decisions such as:
Personalized marketing campaigns
Customer retention strategies
Product recommendations
Identifying premium customers

Dataset
Source: Kaggle – Customer Segmentation Tutorial in Python
File Used: Mall_Customers.csv
Total Records: 200 customers
Features Used for Clustering: Annual Income (k$) and Spending Score (1–100)

Technologies & Libraries
Python
Pandas
NumPy
Matplotlib
Scikit-learn

Machine Learning Workflow
Data Loading
Feature Selection
Data Preprocessing (Scaling using StandardScaler)
Determining Optimal Clusters (Elbow Method)
Applying K-Means Algorithm
Evaluating Clustering (Silhouette Score)
Visualizing Customer Segments

Algorithm Used
K-Means Clustering
K-Means groups data points into K clusters by:
Randomly initializing centroids
Assigning points to nearest centroid
Updating centroid positions
Repeating until convergence

Model Evaluation
Elbow Method used to determine optimal number of clusters
Silhouette Score used to evaluate cluster quality

| Cluster Type                | Description                |
| --------------------------- | -------------------------- |
| High Income – High Spending | Premium Customers          |
| High Income – Low Spending  | Potential Target Customers |
| Low Income – High Spending  | Budget Loyal Customers     |
| Low Income – Low Spending   | Low Engagement Customers   |
| Medium Group                | Average Customers          |
