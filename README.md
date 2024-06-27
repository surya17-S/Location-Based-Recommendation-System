## Location-Based Recommendation System Using Students' Preferences

### Overview

A location-based recommendation system that suggests restaurants and grocery stores to students based on their food preferences. The system clusters students by their food choices and matches them to nearby locations with similar characteristics.

### Prerequisites

Ensure you have the following Python libraries installed:

```sh
pip install numpy pandas matplotlib seaborn requests folium scikit-learn scipy
```

1. **Run the Jupyter Notebook**:

```sh
jupyter notebook notebooks/recommendation_system.ipynb
```

### Key Steps

1. **Load and Clean Data**: Import and preprocess the food choices dataset.
2. **Data Transformation**: Scale the data for clustering.
3. **Clustering**: Apply K-Means, Hierarchical, and DBSCAN clustering algorithms.
4. **Retrieve Location Data**: Use Foursquare API to get nearby venues.
5. **Recommendation**: Match students' clusters to location clusters and suggest relevant venues.

### Visualization

- **Elbow Method**: Determine the optimal number of clusters for K-Means.
- **Silhouette Analysis**: Evaluate the quality of clustering.
- **Dendrogram**: Visualize hierarchical clustering.
- **Folium Map**: Display recommended locations on an interactive map.
