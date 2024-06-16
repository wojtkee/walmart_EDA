# Before starting, please install the required libraries

>pip install -r requirements.txt

>python==3.9.13



# Comparison of all observations using violin plots

I have decided to continue an analysis based on data with missing markdown values that were not used during clustering. The data was divided into 3 clusters that best represented the clustering effects. The graphs show easily identifiable clusters of points visible on the plot. Subsequently, an analysis was conducted between stores across clusters and within clusters themselves. The following results can be observed:

Weekly sales vary significantly between stores within clusters, with the smallest variability observed in cluster 2, which also has the lowest weekly sales among all clusters. The greatest diversity, however, occurs within cluster 1. Cluster 0 shows more variability than cluster 2 but less than cluster 1.

In all clusters, significant temperature differences can be observed.

Cluster 2 is characterized by the highest number of unemployed individuals, with significant variation across individual stores, typically around a median of approximately 10 unemployed persons per store. Clusters 0 and 1 exhibit lower unemployment levels, but still show considerable variability depending on the store.

In cluster 2, the largest fluctuations in fuel prices are observed, typically ranging around 3 and 3.7. Clusters 0 and 1 show similar patterns in their graphs to cluster 2 but are shifted downward, particularly cluster 0, indicating lower fuel prices.
The CPI (Consumer Price Index) graphs show significant differences between regions in cluster 0, characterized by high CPI levels around 210. Cluster 1 exhibits a completely different pattern with large fluctuations ranging from 220 to 120. In cluster 2, CPI levels are generally lower.

The last element of the analysis is regarding markdowns. Markdowns show similar patterns across all clusters, with a median value around 5000. However, there are notable outliers in all clusters where values significantly exceed this median. Cluster 2 has the lowest maximum values, but there are more observations where these higher values occur. The upper part of the violin plot in cluster 2 is wider than in clusters 0 and 1. Cluster 1, in particular, achieves very high values for a small number of observations, suggesting that some stores, or even one store within cluster 1, implemented very large markdowns compared to the rest. Additionally, it should be noted that for markdown5, the leader is a store from cluster 0, where very large discounts were observed that were not present in stores from other clusters.

# Comparison of stores using scatter plots
Additionally, on the scatter plot, it can be observed that there is a relationship where higher markdowns correspond to higher weekly sales for stores in each cluster. This pattern holds true across all clusters: stores with higher markdowns tend to record higher weekly sales. 
Comparing with other plots, the following regularities can be observed: temperature does not significantly affect sales, except for cluster 1 where an increase in temperature is associated with higher sales. However, this is not a universal trend, as there were stores where an increase in temperature did not lead to increased sales. 
No correlations were noted between fuel prices and fluctuations in sales—neither increases nor decreases in fuel prices appeared to consistently impact sales across the clusters. 
A similar situation applies to CPI  and unemployment rates—they do not show consistent correlations with changes in sales across the clusters. The final conclusion drawn is that there is a strong relationship between sales and markdowns. The graphs clearly indicate that as markdowns markdown1-5 increase, sales values also increase.
