# Unsupervised-Learning
In unsupervised learning:
- We can have control over input variables but we do not have dependent variable or control over output variable.
- We have unlabelled data
- Emerging patterns based on similar characteristics or properties.
- Examples: Movie recommendations such as Netflix; Market basket analysis and so on...
# Clustering Technique
- Clustering is a part of unsupervised learning. It is the technique of grouping objects, with heterogeneity between the groups and homogeneity within the groups.
- It can follow agglomerative, divisive or partitioning approach.
-	Distance calculations are done to find similarity and dissimilarity in clustering problems. 
-	The main objective of clustering technique is that 'Sum of squares between the clusters'[SSB] > [SSW] 'Sum of squares within the clusters'.
- Minimisation of Intra-cluster distance and maximisation of inter-cluster distance is called clustering.

In this repository,will be working on agglomerative and k-means clustering:

# Heirarchical Clustering - Agglomerative Clustering:
- It is a Bottom-up approach technique.
- Starts with each object forming a seperate clusters.
- Then it keeps on merging the objects or data points that are close to one another.
- Hierarchical clustering also produces a useful graphical display of the clustering process and results, called a dendrogram.
## Agglomerative Clustering steps involved:
- Start with n clusters where each record will be a cluster.
- Two closest recordsare merged into a cluster.
- At each step , two closest clusters with with smallest distance are merged.
- Repeat till there is a single cluster that includes all the records.
## Advantages of Agglomerative Clustering:
-	No assumptions on the number of clusters.
-	Any desired number of clusters can be obtained by ‘cutting’ the dendrogram at the proper level.
-	Hierarchical clustering may correspond to meaningful taxonomies. 
## Disadvantages of Agglomerative Clustering:
-	Time complexity: not suitable for larger datasets.
-	Very sensitive to outliers. 

