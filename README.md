# K-Means-Clustring-Project

## Dataset

The dataset used in this project is `Live.csv`.

## Libraries Used

The notebook utilizes the following Python libraries:

* **NumPy:** For numerical computations.
* **Pandas:** For data manipulation and analysis.
* **Matplotlib:** For data visualization.
* **Seaborn:** For enhanced data visualization.
* **Scikit-learn:** For machine learning algorithms (KMeans), metrics, and preprocessing.
* **Warnings:** To manage warnings during execution.

## Notebook Structure

The notebook is organized into the following sections:

1.  **Import Libraries:** Imports necessary libraries for the analysis.
2.  **Load Data:** Loads the dataset from the `Live.csv` file into a Pandas DataFrame.
3.  **Data Exploration:**
    * Displays the first few rows of the DataFrame.
    * Provides information about the DataFrame's structure (columns, data types, non-null counts).
    * Generates descriptive statistics for numerical columns.
    * Checks for missing values.
    * Explores the distribution of the target variable.
    * Visualizes data relationships using pair plots and heatmaps.
4.  **Data Preprocessing:**
    * Handles missing values (the specific imputation method is detailed in the notebook).
    * Performs feature scaling using `StandardScaler`.
5.  **K-Means Clustering:**
    * Applies the Elbow Method to determine the optimal number of clusters (k).
    * Performs K-Means clustering with k=2.
    * Evaluates the clustering performance using inertia.
    * Compares cluster labels with the actual labels to calculate classification accuracy.
    * Repeats K-Means clustering with k=4.
    * Evaluates the clustering performance and classification accuracy with k=4.
6.  **Results and Conclusion:**
    * Summarizes the findings of the K-Means clustering analysis.
    * Discusses the optimal number of clusters based on the Elbow Method and classification accuracy.
    * Provides insights into the effectiveness of K-Means for this dataset.

## Key Findings (Based on Notebook Comments)

* The Elbow Method suggests k=2 as a potential optimal number of clusters.
* K-Means with k=2 results in high inertia and low classification accuracy.
* Increasing the number of clusters to k=4 improves classification accuracy.
* This notebook concludes that k=4 might be a more suitable number of clusters for this dataset.
