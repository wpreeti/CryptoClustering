# Module 19 Challenge: Unsupervised Learning - CryptoClustering 
In this challenge we to apply the unsupervised learning technique of K-Means clustering to group cryptocurrencies by their performance to create profitable portfolio recommendations.

## Dataset
[crypto_market_data.csv](Resources/crypto_market_data.csv) - market data of different cryptocurrencies during different time periods

## Overview 
Using the elbow curve method and normalized data, find the optimal k value for the K-Means model uses all original features of the dataset.

Then, using the optimal k value predict the K-Means model to generate 4 clusters of cryptocurrencies. The inertia of each cluster was significant enough to consider reducing the amount of features. 

To reduce the amount of features used, apply Principal Component Analysis to create 3 primary clusters.

Use the PCA data to again calculate the optimal k value for the K-Means model. 

With the optimal k value for the PCA features, we plot the new clusters. 

## Technologies

1. Jupyter - code
2. Conda - Dev environment
3. Pandas - Data analysis
4. Matplotlib - Data visualization
5. Numpy - Data calculations + Pandas support
6. hvPlot - Interactive Pandas plots
7. scikit-learn - KMeans clustering, data normalization, and PCA
8. warnings - To filter out warning messages
      


