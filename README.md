# Foxtail Millet (*Setaria italica*) Morphological Analysis

This repository contains the analysis scripts for the morphological classification of foxtail millet (*Setaria italica*) landraces collected from the Kucapungane (Houcha) tribe in Taiwan.

*Note: The raw trait measurements are currently private pending academic publication. This repo shares the data processing and clustering workflows.*

## Analysis Workflow

A total of 142 landraces were investigated using 30 morphological characters (9 qualitative and 21 quantitative). The code is divided into two main parts:

*   **[01_PCA_KMeans_Clustering.ipynb](./01_PCA_KMeans_Clustering.ipynb)**: Data preprocessing, PCA feature extraction, and K-Means clustering.
*   **[02_tSNE_Evaluation.ipynb](./02_tSNE_Evaluation.ipynb)**: High-dimensional visualization using t-SNE to compare and evaluate the clustering results.

## Tools
* Python (pandas, numpy)
* scikit-learn
* matplotlib, seaborn, bioinfokit
