# Customer Segmentation using Machine Learning 

This project demonstrates the power of machine learning to perform customer segmentation based on purchasing behaviour. Our dataset includes information about the number of transactions, unique customers, unique products, and categories. The data was analyzed to find patterns, such as the percentage of cancelled orders and the frequency of orders from different categories.

## Project Overview 

This project involves the following steps:

1. **Data Preprocessing:** The dataset was first separated to isolate cancelled orders from the main dataset. This processed dataset includes data for 79,309 unique customers who bought 62,531 unique products in 202,314 transactions.

2. **Clustering:** The K-Means algorithm was used for clustering. The Elbow method and the Silhouette score determined the optimal number of clusters.

3. **Classification:** Multiple machine learning classifiers were trained, including Support Vector Classifier, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost Classifier and Ensemble voting classifier. These classifiers were evaluated based on precision, recall, f1 score and accuracy metrics.

4. **Testing:** The classifiers were tested on a separate dataset. The accuracy of these classifiers was then determined.

5. **Customer Segmentation:** The results of the clustering and classification were used to segment customers based on their purchasing behaviours.

## Installation

Include the requirements and installation instructions for the software needed to run your project.

## Usage

Explain how to use your project. Provide code examples, screenshots or command line examples.

## Results

The project successfully segmented customers into 24 distinct clusters. The results showed that Random Forest, Gradient Boosting, and Decision Tree classifiers predict better customer behaviours concerning the categories they purchased. The clusters formed were distinct and showed varied behaviors such as buying from a single category or buying frequently.

## Conclusion and Future Work

This project presents a promising effect of using machine learning on customer segmentation. The segmentation can help businesses devise marketing strategies, manage supply and demand, and identify products associated with specific segments. 

In the future, additional analysis can be performed to understand the relationship between future orders from previous orders, the geographical location of orders, and customer demographics.
