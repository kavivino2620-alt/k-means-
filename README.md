# k-means-
import numpy as np

def initialize_centroids(X, K):
    indices = np.random.choice(len(X), K, replace=False)
    centroids = X[indices]
    return centroids
