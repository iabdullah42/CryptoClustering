# Cryptocurrency Clustering with K-Means and PCA

Groups cryptocurrencies by price-change behavior (24h to 1y) using unsupervised learning.

**Approach**
- Scale the market data, then use the elbow method to choose *k* → **k = 4**
- Cluster with K-means on the scaled data
- Reduce to 3 principal components, which explain **89.5%** of the variance, and re-cluster. *k* stays at 4, and the clusters separate more cleanly
- Read the PCA loadings to see which price-change windows drive each component

**Notebook:** `Starter_Code/Crypto_Clustering.ipynb`

**Tools:** Python, pandas, scikit-learn (KMeans, PCA)

*Coursework from the OSU AI Bootcamp.*
