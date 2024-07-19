# Clusterization
Clustering with K-means requires specifying a presumed number of clusters, which is often problematic. Typically, the proposed solution is the elbow method, but this approach can be, well, not particularly convincing. Therefore, we aim to explore an alternative solution using self-organizing Kohonen maps (SOMs). This technique projects our multidimensional data space into a 2D map while preserving the topology. In simple terms, data points that are close in the n-dimensional space will remain close on the 2D map. This visualization will help us to determine the number of clusters. Once we've established the appropriate k, we perform K-means clustering and label our data accordingly.
<br><br>
Data dource: https://www.kaggle.com/datasets/vipulgohel/clustering-pca-assignment
