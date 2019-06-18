# KDD2019_K-Multiple-Means (KMM)

Implementation for the paper "K-Multiple-Means: A Multiple-Means Clustering Method with Specified K Clusters", which has been accepted by KDD'2019 as an Oral Paper, in the Research Track.

## Abstract
In this paper, we make an extension of K-means for the clustering of multiple means. The popular K-means clustering uses only one center to model each class of data. However, the assumption on the shape of the clusters prohibits it to capture the non-convex
patterns. Moreover, many categories consist of multiple subclasses which obviously cannot be represented by a single prototype. We
propose a K-Multiple-Means (KMM) method to group the data points with multiple sub-cluster means into specified k clusters.
Unlike the methods which use the agglomerative strategies, the proposed method formalizes the multiple-means clustering problem
as an optimization problem and updates the partitions of m subcluster means and k clusters by an alternating optimization strategy.
Notably, the partition of the original data with multiple-means representation is modeled as a bipartite graph partitioning problem
with the constrained Laplacian rank. We also show the theoretical analysis of the connection between our method and the K-means
clustering. Meanwhile, KMM is linear scaled with respect to n. Experimental results on several synthetic and well-known realworld
data sets are conducted to show the effectiveness of the proposed algorithm.

## Short Promotion Video
which will be released soon.

## Oral Presentation Video
which will be released soon.

## Others
KMM can not only obtain the clustering result but also obtain the corresponding multi-mean value, which can be applied to many fields like kmeans, such as nearest-neighbor search, data compression, etc. KMM can also be used as an anchor-based spectral clustering method, which can find better anchors and achieve better clustering result. 

If you find this code useful in your research, please cite the paper.

## Reference:

Feiping Nie, Cheng-Long Wang, Xuelong Li, "K-Multiple-Means: A Multiple-Means Clustering Method with Specified K Clusters," in *Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD'19)*, Anchorage, AK, USA, August 4–8, 2019.
