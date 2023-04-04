Mall Customer Segmentation:
This project aims to perform customer segmentation for a mall using clustering techniques. The dataset used for this project contains information on the annual income, age, and spending score of mall customers.

Data:
The dataset used in this project contains information on 200 customers.The data was sourced from Kaggle.

Dataset:
The dataset contains the following features;
CustomerID: Unique identifier for each customer
Gender: Gender of the customer
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): Score assigned to the customer based on their spending habits and purchasing behavior


Approach:
Two clustering models were developed using the KMeans algorithm and the PCA dimensionality reduction technique;
Clustering based on annual income and spending score, with 5 clusters.
Clustering based on age, annual income, and spending score, with 5 clusters.
The number of clusters for each model was determined using the elbow method. The silhouette score was used to evaluate the performance of the clustering models.

Results:
The silhouette score for the first clustering model, which used only annual income and spending score, was 0.55. The silhouette score for the second clustering model, which used age, annual income, and spending score, was 0.42.


Based on the clustering results, the following customer segments were identified:

High Income, High Spending: These customers have a high annual income and high spending score. They are the most profitable customers for the mall and should be targeted with exclusive and high-end products to maintain their loyalty.
High Income, Low Spending: These customers have a high annual income but low spending score. They are potential customers who can be targeted with discounts and promotions to increase their spending.
Average Income, Average Spending: These customers have an average annual income and an average spending score. They are the largest group of customers and should be targeted with a balanced marketing strategy.
Low Income, High Spending: These customers have a low annual income but high spending score. They are price-insensitive customers who can be targeted with low-priced products and deals.
Low Income, Low Spending: These customers have a low annual income and low spending score. They are not profitable for the mall and should not be the target of any marketing efforts.

Conclusion:
Customer segmentation can help the mall develop targeted marketing strategies for each customer segment. For example, low-income, high-spending customers may respond well to promotions and discounts, while high-income, low-spending customers may be more interested in exclusive or luxury products.
