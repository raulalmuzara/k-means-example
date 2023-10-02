# Example of clustering with k-means
Methodology for partitioning a dataset into clusters using the k-means algorithm. First, we will determine the optimal number of clusters using the elbow method with the inertias of several models with different values of k. Then, we will visualize the partitions provided by the algorithm with different seeds to check the convergence of the method to similar clusters and centroids. Finally, we will predict the cluster that would correspond to new points. The KMeans implementation from scikit-learn has been used.

*k-means-code.ipynb* is the notebook containing the Python code and *data-clustering.csv* is the dataset containing 150 two-dimensional points.
