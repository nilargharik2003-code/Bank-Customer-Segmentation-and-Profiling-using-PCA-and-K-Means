# Bank-Customer-Segmentation-and-Profiling-using-PCA-and-K-Means
📌 Project Overview

This project focuses on segmenting bank customers based on their demographic, financial, and campaign behavior using unsupervised machine learning techniques.
The goal is to identify meaningful customer segments that can support targeted marketing and engagement strategies.

🎯 Objective

Discover natural customer groupings without labeled data

Reduce high-dimensional data while preserving important information

Interpret clusters in a business-relevant and actionable manner

📂 Dataset

Bank marketing dataset containing customer demographics, financial attributes, and campaign interaction history

Key features include age, balance, loans, contact history, and campaign outcomes

🛠️ Methodology
1️⃣ Data Preprocessing & EDA

Performed univariate, bivariate, and multivariate exploratory data analysis

Handled missing values and encoded categorical variables

Treated skewed numerical features:

Applied signed log transformation to balance to preserve negative overdraft behavior

Scaled numerical features to ensure fair distance calculations

2️⃣ Dimensionality Reduction

Applied Principal Component Analysis (PCA)

Retained 95% of total variance to reduce noise and multicollinearity

Enabled more stable and efficient clustering

3️⃣ Clustering

Used K-Means clustering on PCA-transformed data

Selected optimal number of clusters using:

Elbow Method

Silhouette Analysis

Identified 6 distinct customer segments

4️⃣ Cluster Interpretation

Analyzed cluster-wise:

Age distribution

Financial strength (balance)

Campaign frequency

Previous engagement history

Combined numerical and categorical insights to create customer personas

Validated clusters using 2D and 3D PCA visualizations

📊 Key Findings

Customers differ more by behavior and engagement history than by demographics alone

Identified segments such as:

High-value but under-engaged customers

Over-contacted low-response customers

New and untapped customers

Previously engaged but unsuccessful segments

Cluster overlap in low-dimensional projections is expected for real-world customer data and does not reduce interpretability

🧠 Why K-Means?

Suitable for large, continuous, and scaled datasets

Efficient and interpretable for customer segmentation

Moderate silhouette scores are realistic for real-world behavioral data

🧪 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

PCA

K-Means

Silhouette Analysis

📈 Results

Reduced high-dimensional data while preserving structure

Achieved stable and interpretable clusters

Derived actionable insights for customer targeting and marketing strategies

🚀 Future Improvements

Explore Gaussian Mixture Models (GMM) for soft clustering

Compare with Hierarchical Clustering

Integrate supervised learning using campaign response as target

Add automated cluster evaluation metrics

🧩 Conclusion

This project demonstrates how unsupervised learning, combined with careful preprocessing and domain-aware feature engineering, can uncover meaningful customer segments and support data-driven decision-making in the banking domain.
