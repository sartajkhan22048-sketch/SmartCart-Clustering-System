# SmartCart Clustering System

## Project Overview
SmartCart Clustering System is a customer segmentation project using Machine Learning clustering techniques. The project analyzes customer data to identify groups with similar characteristics and purchasing behavior.

## Objectives
- Analyze customer data.
- Perform data preprocessing and feature engineering.
- Apply clustering algorithms to group customers.
- Use visualizations to understand customer segments.
- Evaluate clustering quality.

## Dataset
The dataset contains 2,240 customer records and 22 columns.

File: `smartcart_customers.csv`

The dataset includes features such as:
- Customer income
- Education and marital status
- Purchase history
- Website visits
- Customer recency
- Complaints and campaign response

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PCA
- K-Means Clustering
- Agglomerative Clustering

## Project Workflow
1. Load the customer dataset.
2. Explore and preprocess the data.
3. Encode categorical features.
4. Scale numerical features.
5. Apply Principal Component Analysis (PCA).
6. Determine suitable clusters using the Elbow Method.
7. Evaluate clusters using the Silhouette Score.
8. Apply K-Means and Agglomerative Clustering.
9. Visualize and interpret the results.

## Project Files
- `smartcart.ipynb` — Jupyter Notebook containing the code and analysis.
- `smartcart_customers.csv` — Customer dataset.
- `requirements.txt` — Required Python libraries.

## How to Run
1. Download or clone this repository.
2. Install the required libraries using:

   `pip install -r requirements.txt`

3. Open `smartcart.ipynb` in JupyterLab.
4. Run the notebook cells in order.

## Results
The project explores customer groups using clustering algorithms. Add the final number of clusters, evaluation scores, and key findings after verifying the notebook results.

## Future Improvements
- Develop a customer segmentation dashboard.
- Compare different clustering approaches.
- Generate actionable insights for marketing strategies.

## Author
Add your name here.

