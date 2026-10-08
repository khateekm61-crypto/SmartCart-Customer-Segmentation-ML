# SmartCart Customer Segmentation using Machine Learning

## Project Overview

SmartCart Customer Segmentation is an unsupervised machine learning project that analyzes customer demographics, purchasing behavior, spending patterns, website activity, and customer response to identify meaningful customer segments.

The project uses clustering techniques to discover groups of customers with similar behavioral patterns and generate business-oriented insights for personalized marketing and customer retention.

## Problem Statement

SmartCart serves customers with different purchasing and engagement behaviors. Using the same marketing strategy for every customer can result in inefficient marketing and missed opportunities to identify high-value or low-engagement customers.

The objective of this project is to build a customer segmentation system using unsupervised machine learning and group customers into meaningful clusters based on their characteristics and behavior.

## Dataset

The dataset contains:

- **2,240 customers**
- **22 attributes**

The features cover:

- Customer demographics
- Income
- Education
- Marital status
- Household information
- Product spending
- Purchase frequency
- Website activity
- Recency
- Customer complaints
- Campaign response

### Major Features

- `Income`
- `Year_Birth`
- `Education`
- `Marital_Status`
- `Kidhome`
- `Teenhome`
- `MntWines`
- `MntFruits`
- `MntMeatProducts`
- `MntFishProducts`
- `MntSweetProducts`
- `MntGoldProds`
- `NumDealsPurchases`
- `NumWebPurchases`
- `NumCatalogPurchases`
- `NumStorePurchases`
- `NumWebVisitsMonth`
- `Recency`
- `Complain`
- `Response`

## Project Objectives

- Understand customer behavior
- Analyze spending patterns
- Identify customer groups
- Apply unsupervised machine learning
- Determine an appropriate number of clusters
- Compare clustering approaches
- Profile the resulting customer segments
- Generate business-oriented marketing insights

## Project Workflow

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Outlier Handling
      ↓
Categorical Encoding
      ↓
Feature Scaling
      ↓
PCA
      ↓
Elbow Method & Silhouette Analysis
      ↓
K-Means Clustering
      ↓
Agglomerative Clustering
      ↓
Cluster Profiling
      ↓
Business Insights
