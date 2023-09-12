## Overview

The goal of the Crypto Clustering project is to leverage unsupervised learning techniques, with a focus on K-means clustering, to predict whether cryptocurrencies are affected by price changes over either a 24-hour or 7-day timeframe. Additionally, the project explores the impact of dimensionality reduction achieved through Principal Component Analysis (PCA) on the results of clustering.

## Process

1. Begin by importing and preprocessing the dataset.
2. Normalize the data using the StandardScaler method.
3. Utilize the elbow method to identify the optimal value for 'k' (the number of clusters).
4. Apply the K-means algorithm to cluster cryptocurrencies using the original scaled data.
5. Implement Principal Component Analysis (PCA) to reduce the feature set to three principal components.
6. Determine the best 'k' value for clustering using the PCA-transformed data.
7. Proceed to cluster cryptocurrencies using K-means with the PCA-processed data.
8. Visualize and compare the results using hvPlot.

## Conclusion

This project aims to investigate the impact of feature reduction on data clustering using the K-means algorithm. By analyzing and comparing the clustering results obtained from the original dataset and the dataset processed using Principal Component Analysis (PCA), we can gain valuable insights into how dimensionality reduction influences the clustering process.

## Language and Libaries 

- Python
- Pandas
- NumPy
- Scikit-learn
- hvPlot
