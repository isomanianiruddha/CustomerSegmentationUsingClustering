# Customer Segmentation using Clustering

This project focuses on segmenting customers into different groups based on their purchasing behavior using unsupervised machine learning techniques. It helps businesses understand customer patterns and improve targeted marketing strategies.

Dataset
* File: `Mall_Customers.csv`
* Features:
  * Customer ID
  * Gender
  * Age
  * Annual Income (k$)
  * Spending Score (1–100)

Technologies Used
* Python 
* Pandas
* NumPy
* Matplotlib 
* Seaborn
* Scikit-learn

Data Preprocessing
* Checked for missing values
* Selected relevant features
* Feature scaling using StandardScaler
* Dimensionality reduction using PCA

Models & Techniques Used
Elbow Method
* Used to determine the optimal number of clusters (K)

K-Means Clustering
* Groups customers into K clusters based on similarity

Hierarchical Clustering (Agglomerative)
* Builds clusters step-by-step using a bottom-up approach

DBSCAN
* Density-based clustering
* Identifies clusters of arbitrary shape and detects noise

Principal Component Analysis (PCA)
* Reduces dimensionality for better visualization and performance

Results
* Optimal number of clusters identified using Elbow Method
* Different clustering techniques produced meaningful customer segments
* PCA improved visualization of clusters in 2D space

Key Insights
* High income & high spending customers are premium targets
* Clustering helps identify different customer groups
* DBSCAN effectively detects outliers
* PCA helps in simplifying complex data

Conclusion
This project demonstrates how multiple clustering techniques can be used to segment customers effectively. Comparing different models provides deeper insights into customer behavior and improves decision-making.

Future Improvements
* Hyperparameter tuning for clustering algorithms
* Use real-time data for dynamic segmentation
* Build a dashboard for visualization

Author : **Aniruddha Somani**
