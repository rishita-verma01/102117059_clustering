# 102117059_clustering
Clustering
## Perform Cluster Analysis: 
This part of the code iterates over each combination of clustering algorithm and preprocessing technique to perform cluster analysis on the dataset.
## Check for One Cluster: 
After applying the clustering algorithm to the preprocessed data, the code checks if only one cluster is produced by counting the number of unique cluster labels (np.unique(labels)).
## Handle One Cluster Case: 
If only one cluster is produced, it indicates that certain evaluation metrics cannot be computed because they require at least two clusters. In this case, the code assigns NaN values to all evaluation metrics for that combination of clustering algorithm and preprocessing technique.
## Calculate Evaluation Metrics:
If more than one cluster is present, the code proceeds with calculating the evaluation metrics as before.
## Results Storage: 
The results of the analysis, including the algorithm name, preprocessing technique, and evaluation metric scores (or NaN values if applicable), are stored in the results list.
