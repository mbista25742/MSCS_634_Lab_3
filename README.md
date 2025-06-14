# MSCS_634_Lab_3
Lab 3: Clustering Analysis Using K-Means and K-Medoids Algorithms

## Purpose
The purpose of this lab is to explore and compare the performance of two popular clustering algorithms — K-Means and K-Medoids — on the Wine dataset. The objective is to understand how these methods group data points based on chemical properties and to evaluate their clustering quality using Silhouette Score and Adjusted Rand Index (ARI).

## Key Insights
- The dataset contains 178 samples with 13 features each.
- K-Means achieved a higher Silhouette Score (0.2849) and a superior ARI (0.8975), indicating better-defined clusters and closer alignment with the true wine classes.
- K-Medoids showed slightly lower scores (Silhouette: 0.2660, ARI: 0.7263) but is known to be more robust to noise and outliers.
- Visual analysis suggested that while K-Means clusters were more compact, K-Medoids clusters could better handle irregular shapes and potential outliers.

## Challenges and Decisions
- Standardization of features was critical to ensure fair clustering performance since features vary widely in scale.
- Installation and usage of the `scikit-learn-extra` package was necessary to implement K-Medoids.
- Choosing appropriate evaluation metrics (Silhouette Score for internal cohesion and ARI for external validation) provided a comprehensive understanding of clustering effectiveness.
- The balance between computational efficiency (favoring K-Means) and robustness to outliers (favoring K-Medoids) was an important consideration in interpreting the results.
