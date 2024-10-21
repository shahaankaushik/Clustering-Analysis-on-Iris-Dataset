# Clustering Analysis on Iris Dataset

This project demonstrates the application of various clustering algorithms on the Iris dataset using Python and scikit-learn.

## Overview

The analysis includes the following steps:
1. Data preprocessing (normalization and dimensionality reduction)
2. Application of clustering algorithms (K-Means, Hierarchical, and Mean Shift)
3. Evaluation of clustering results using multiple metrics

## Dependencies

- Python 3.x
- scikit-learn
- numpy
- pandas

## Algorithms Used

1. K-Means Clustering
2. Hierarchical Clustering
3. Mean Shift Clustering

## Evaluation Metrics

The following metrics were used to evaluate the clustering results:
1. Silhouette Score
2. Calinski-Harabasz Index
3. Davies-Bouldin Index

## Results

| Algorithm    | Silhouette | Calinski-Harabasz | Davies-Bouldin |
|--------------|------------|-------------------|----------------|
| K-Means      | 0.459378   | 241.893262        | 0.834000       |
| Hierarchical | 0.446689   | 222.719164        | 0.803467       |
| Mean Shift   | 0.581750   | 251.349339        | 0.593313       |

## Conclusion

Based on the evaluation metrics, Mean Shift clustering appears to perform the best on this dataset, with the highest Silhouette score, highest Calinski-Harabasz index, and lowest Davies-Bouldin index.

## Usage

To run the analysis:
1. Ensure all dependencies are installed
2. Run the Jupyter notebook `clustering_analysis.ipynb`

## Future Work

- Experiment with other clustering algorithms
- Try different preprocessing techniques
- Visualize the clustering results
