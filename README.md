Customer Segmentation using Unsupervised Learning

🔹 Problem Statement
Retailers often struggle to understand diverse customer behaviors. Without segmentation, marketing campaigns are generic, leading to wasted ad spend and poor engagement.
Goal: Apply unsupervised learning to group customers into meaningful segments for personalized marketing, product recommendations, and loyalty programs.

🔹 Dataset
Source: Mall Customer Segmentation Dataset (Kaggle) (kaggle.com in Bing)

Features:

CustomerID

Genre

Age

Annual Income (k$)

Spending Score (1–100)

🔹 Methodology
Data Preprocessing

Encode categorical variables (Gender).

Normalize numerical features (Income, Spending Score).

Exploratory Data Analysis (EDA)

Distribution plots for Age, Income, Spending Score.

Correlation heatmap.

Scatter plots (Income vs Spending Score).

Clustering Models

K‑Means (baseline).

Hierarchical Clustering (validation).

DBSCAN (outlier detection).

Cluster Evaluation

Elbow Method (SSE).

Silhouette Score.

🔹 Results
Identified 5 customer segments:

Budget Shoppers → Low income, low spending.

Value Seekers → Medium income, medium spending.

Luxury Enthusiasts → High income, high spending.

Young Trendsetters → Younger age, high spending despite medium income.

Cautious Savers → High income, low spending.

🔹 Business Impact
Targeted Marketing: Luxury segment gets premium offers; budget shoppers get discounts.

Product Strategy: Trendsetters can be targeted with new launches.

Retention: Identify savers and design loyalty programs to increase spending.

ROI Impact: Personalized campaigns reduce wasted ad spend and increase conversion rates.

🔹 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit‑Learn

ML Techniques: K‑Means, Hierarchical Clustering, DBSCAN

Visualization: Cluster plots, PCA for dimensionality reduction

