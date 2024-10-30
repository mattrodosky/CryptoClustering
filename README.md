# Cryptocurrency Clustering Analysis
Module 11 Challenge

## Overview
This project applies K-means clustering and Principal Component Analysis (PCA) to classify cryptocurrencies based on their price fluctuations across various timeframes. The analysis examines price changes over intervals of 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year.

## Project Structure
1. Data Loading and Preprocessing
   - Load cryptocurrency market data
   - Normalize data using StandardScaler

2. K-means Clustering on Original Data
   - Determine optimal number of clusters using elbow method
   - Perform clustering and visualize results

3. Principal Component Analysis
   - Reduce data to three principal components
   - Analyze explained variance

4. K-means Clustering on PCA Data
   - Determine optimal number of clusters for PCA data
   - Perform clustering and visualize results

5. Feature Analysis
   - Determine weights of each feature on principal components

## Key Findings
- The optimal number of clusters (k) was determined to be 4 for both original and PCA-reduced data.
- PCA reduced the dataset to three principal components while retaining 89.50% of the total variance.
- Analysis of feature weights on principal components revealed that each PC had some significant influences both positively and negatively

## How to Run
1. Clone the repository
2. Run the Jupyter notebook: `jupyter notebook Crypto_Clustering.ipynb`
3. All libraries and dependencies can be installed within the notebook
## Author
Matthew Rodosky