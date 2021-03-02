# market_segmentation_illinois


### Objective: to identify a set of characteristic statewide market clusters for use in targeted marketing. 

Data: Access and Proximity to Grocery Store (Food Environment Atlas)

- 102 rows (counties), 41 columns

Preprocessing for clustering:
- Feature scaling
- Imputation using column means

Other clustering methods:
- Hierarchical clustering (Dendrogram)
  - determines cluster assignments by building a hierarchy
- Density-based clustering (DBSCAN)
  - determines cluster assignments based on the density of data points in a region

Using SSE, we have identified a K = 18

Using the folium package, We can visualize 10 clusters of counties on the map of Illinois


Two example metrics are below:

Indicator: Population, low access to store
Definition: Number of people in a county living more than 1 mile from a supermarket or large grocery store if in an urban area, or more than 10 miles from a supermarket or large grocery store if in a rural area.

Indicator: Population, low access to store (percent)
Definition: Percentage of people in a county living more than 1 mile from a supermarket or large grocery store if in an urban area, or more than 10 miles from a supermarket or large grocery store if in a rural area.







