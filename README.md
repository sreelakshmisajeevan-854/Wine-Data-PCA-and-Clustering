# PCA and Clustering Analysis

## Objective

The objective of this project is to explore dimensionality reduction using Principal Component Analysis (PCA) and analyze its impact on clustering performance.

The project compares clustering results obtained from the original dataset with those obtained after applying PCA.

## Project Overview

This project follows a machine learning workflow involving:

- Exploratory Data Analysis
- Feature standardization
- Principal Component Analysis (PCA)
- K-Means clustering
- Clustering evaluation
- Comparison of original and PCA-transformed data

## Tasks Performed

### 1. Exploratory Data Analysis (EDA)

- Loaded and explored the dataset.
- Examined the shape, data types, and summary statistics.
- Analyzed feature distributions.
- Created histograms, box plots, and density plots.
- Investigated correlations between features using a correlation matrix.

### 2. Dimensionality Reduction Using PCA

- Standardized numerical features before applying PCA.
- Applied Principal Component Analysis (PCA).
- Analyzed explained variance of each principal component.
- Used a scree plot and cumulative explained variance to determine the appropriate number of components.
- Transformed the original dataset into PCA components.

### 3. Clustering Using Original Data

K-Means clustering was applied to the original standardized dataset.

The clustering results were:

- Visualized using appropriate plots.
- Evaluated using clustering performance metrics.

The following metrics were used:

- Silhouette Score
- Davies-Bouldin Index

### 4. Clustering Using PCA Data

K-Means clustering was also applied to the PCA-transformed dataset.

The results were:

- Visualized using PCA components.
- Evaluated using Silhouette Score.
- Evaluated using Davies-Bouldin Index.

### 5. Comparison of Clustering Results

The clustering results from the original dataset and PCA-transformed dataset were compared based on:

- Silhouette Score
- Davies-Bouldin Index
- Cluster separation
- Visualization of clusters

The impact of dimensionality reduction on clustering performance was analyzed.

## PCA

Principal Component Analysis is a dimensionality reduction technique that transforms correlated features into a smaller number of uncorrelated principal components while retaining as much of the original variation as possible.

PCA can help:

- Reduce the number of features.
- Remove redundant information.
- Improve computational efficiency.
- Make high-dimensional data easier to visualize.
- Reduce noise in some datasets.

## K-Means Clustering

K-Means is an unsupervised machine learning algorithm that divides data into a predefined number of clusters based on similarity between observations.

The number of clusters can be selected using techniques such as:

- Elbow Method
- Silhouette Score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Structure

```text
PCA-and-Clustering-Analysis/
│
├── PCA_and_Clustering_Analysis.ipynb
├── wine.csv
└── README.md
