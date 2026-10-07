# R Programming Lab 7 — Customer Segmentation and Predictive Analytics

## Aim

To use the UCI Online Retail transaction dataset to create customer-level features, segment customers, visualize clusters, and predict membership in a high-value customer segment using R.

## Dataset

**UCI Online Retail Dataset**

The dataset contains online retail transaction information such as:

- Invoice number
- Product code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

The dataset is obtained from the **UCI Machine Learning Repository**.

Dataset Link:  
https://archive.ics.uci.edu/dataset/352/online+retail

## Experiment Workflow

1. Load the Online Retail dataset.
2. Inspect and clean the transaction data.
3. Create customer-level RFM and purchasing features.
4. Use the Elbow Method to determine the suitable number of clusters.
5. Perform K-Means clustering.
6. Perform Hierarchical Clustering.
7. Evaluate clustering using the Silhouette Score.
8. Apply PCA for 2D visualization.
9. Create an interactive 3D visualization using Plotly.
10. Profile and interpret the customer clusters.
11. Identify a high-value customer segment.
12. Train a Random Forest classifier.
13. Train an SVM classifier.
14. Compare the classification results.
15. Analyze feature importance and provide marketing recommendations.

## Technologies and Libraries Used

- R Programming
- K-Means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- Random Forest
- Support Vector Machine (SVM)
- ggplot2
- dplyr
- tidyr
- cluster
- caret
- randomForest
- e1071
- pROC
- Plotly
- readxl
- knitr

## Key Concepts

### RFM Analysis

Customer behavior is analyzed using:

- **Recency** – How recently a customer made a purchase.
- **Frequency** – How frequently a customer makes purchases.
- **Monetary Value** – How much money a customer spends.

### Customer Segmentation

K-Means and Hierarchical Clustering are used to divide customers into groups with similar purchasing behavior.

### Classification

Random Forest and Support Vector Machine models are used to predict whether a customer belongs to the identified high-value customer segment.

## Results

The experiment generates:

- Cleaned transaction data
- Customer-level RFM features
- K-Means customer segments
- Hierarchical clustering results
- Silhouette Score evaluation
- PCA-based cluster visualization
- Interactive 3D visualization
- Customer cluster profiles
- High-value customer classification
- Random Forest and SVM performance comparison
- Feature importance analysis
- Marketing recommendations

## Conclusion

This experiment demonstrates how R can be used for customer segmentation and predictive analytics. Clustering techniques help identify groups of customers with similar purchasing behavior, while classification models can be used to predict high-value customers based on their characteristics.

## Author

**Ketki Gaikwad**

Computer Engineering  
Vidyalankar Institute of Technology
