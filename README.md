# CSCA 5632 Final Project: Customer Segmentation for Marketing Strategy

This project applies unsupervised machine learning techniques to segment customers based on their purchasing behaviors, demographics, and engagement metrics. By identifying distinct customer groups, businesses can tailor their marketing approaches, product recommendations, and customer service strategies to better meet the needs of different customer segments.

## Project Overview

### Problem Statement
The primary objective of this analysis is to identify natural groupings within a retail company's customer base that may not be immediately apparent through conventional business analysis. Specifically, we aim to:
1. Discover distinct customer segments based on purchasing patterns and demographics.
2. Characterize these segments to understand their unique behaviors and preferences.
3. Provide actionable insights for targeted marketing campaigns and personalized customer experiences.

### Dataset
The analysis uses the "Mall Customer Segmentation Data" available on Kaggle. This dataset contains 200 observations with the following features:
- `CustomerID`: Unique identifier for each customer.
- `Gender`: Male or Female.
- `Age`: Customer's age.
- `Annual Income (k$)`: Customer's annual income in thousands of dollars.
- `Spending Score (1-100)`: Score assigned by the mall based on customer spending behavior and purchasing data.

## Key Features of the Project

1. **Exploratory Data Analysis (EDA)**:
   - Visualizations of gender, age, income, and spending score distributions.
   - Correlation analysis to understand relationships between features.

2. **Feature Engineering**:
   - Encoding categorical variables.
   - Scaling numerical features for clustering.

3. **Dimensionality Reduction**:
   - Principal Component Analysis (PCA) to visualize data in a reduced-dimensional space.

4. **Clustering Techniques**:
   - **K-Means Clustering**:
     - Optimal number of clusters determined using the elbow method and silhouette analysis.
     - Visualization of clusters in PCA-reduced space and feature space.
   - **Hierarchical Clustering**:
     - Dendrogram analysis to determine the number of clusters.
     - Visualization of hierarchical clusters.

5. **Cluster Profiling**:
   - Detailed analysis of each cluster's demographics and behaviors.
   - Actionable insights for marketing strategies.

## Results and Insights

- Identified 5 distinct customer segments with unique characteristics and behaviors.
- Provided actionable marketing strategies for each segment, including personalized marketing, loyalty programs, and re-engagement campaigns.

## Requirements

To run the project, install the required Python libraries using the `requirements.txt` file:
```bash
pip install -r requirements.txt
