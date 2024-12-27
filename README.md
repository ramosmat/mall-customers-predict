# Mall Customer Segmentation

This repository presents a machine learning project for segmenting mall customers based on their purchasing behavior and demographic characteristics. Using clustering techniques, the project aims to identify distinct customer groups that can guide targeted marketing strategies.

## Dataset

The dataset used in this project includes the following features:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature.

The dataset is publicly available from the [Mall Customers Dataset on Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python).

## Key Libraries

The following Python libraries were used in this project:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For clustering and dimensionality reduction techniques.

## Machine Learning Techniques

This project focuses on unsupervised learning, specifically clustering algorithms:

- **K-Means Clustering**

## Project Workflow

1. **Data Preprocessing**:
   - Checking for and handling missing values (no missing data in this dataset).
   - Encoding categorical variables (e.g., converting 'Gender' into numerical form).
   - Feature scaling for clustering algorithms sensitive to data scale with StandardScaler.

2. **Clustering**:
   - Implementing and comparing clustering algorithms (e.g., K-Means, Hierarchical, and DBSCAN).
   - Using the **Elbow Method** to determine the optimal number of clusters.

3. **Visualization**:
   - Analyzing the characteristics of each identified customer segment.

4. **Insights**:
   - Segmenting customers into groups such as high spenders, budget-conscious shoppers, etc.

## Results Summary

The project identified the following customer segments (examples):
- **Cluster 1**: Medium-income, moderate-spending customers.
- **Cluster 2**: High-income, high-spending customers.
- **Cluster 3**: Low-income, high-spending customers.
- **Cluster 4**: High-income, low-spending customers.
- **Cluster 5**: Low-Income, low-spending customers.

These insights can help in creating targeted marketing strategies tailored to each segment.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/ramosmat/mall-customers-predict.git
   ```

2. Navigate to the project directory:
   ```bash
   cd mall-customers-predict
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook script.ipynb
   ```

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.