# mall-segmentation-task-8
Objective
Perform customer segmentation using K-Means Clustering, an unsupervised machine learning technique. The aim is to identify meaningful customer groups based on their annual income and spending score.

Technologies & Libraries
Python
Pandas
Scikit-learn
Matplotlib
Seaborn

Steps Performed
1. Load and Explore Dataset
Basic inspection and selection of relevant features.
2. Elbow Method
Used to determine the optimal number of clusters (K) by plotting inertia (WCSS) vs K.
3. Apply K-Means Clustering
Clusters customers based on income and spending score using KMeans from scikit-learn.
4. Visualize Clusters
Color-coded scatter plots showing customer groups.
Cluster centers marked with black 'X'.
5. Interpret Cluster Centers

Analyzed average income and spending for each cluster to define group behavior:
Low income, low spending
High income, high spending
Low income, high spending (impulsive)
High income, low spending (cautious)
Moderate customers
6. Evaluate Model
Used Silhouette Score to assess how well-separated the clusters are.
