 K-Nearest Neighbors on Custom 3D Dataset (2D Projection)
 Project Overview
This project demonstrates the behaviour of the K-Nearest Neighbors (KNN) classifier on a custom dataset (3D_dataset.csv). Although the dataset contains three dimensions originally, we focus on two features (feature1 and feature2) for visualisation purposes. The goal is to explore how different distance metrics (Euclidean, Manhattan, Minkowski) affect decision boundaries and classification accuracy.

 Features
Load and preprocess a custom dataset (3D_dataset.csv)

Feature scaling with StandardScaler

Train/test split for evaluation

KNN classifier with varying distance metrics:

Euclidean (p=2)

Manhattan (p=1)

Minkowski (p=3)

Visualisation of:

Dataset scatter plot (neutral colours)

Decision boundaries for each metric

