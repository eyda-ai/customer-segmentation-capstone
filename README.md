# Customer Segmentation using K-Means Clustering

## Project Overview
This project applies unsupervised machine learning techniques to segment customers based on demographic and purchasing behavior. Using the K-Means clustering algorithm, customers are grouped into meaningful segments that help businesses better understand their customers.

## Business Context
Retail businesses serve customers with diverse income levels, purchasing behaviors, and spending habits. Without effective customer segmentation, marketing campaigns are often applied uniformly to all customers, which can lead to inefficient marketing spending and lower customer engagement.

Customer segmentation helps businesses identify groups of customers with similar characteristics and behaviors. By understanding these patterns, companies can design targeted marketing strategies, improve customer experience, and allocate marketing resources more efficiently.

## Problem Statement
The objective of this project is to apply **unsupervised machine learning**, specifically the **K-Means clustering algorithm**, to segment customers based on their **age, annual income, and spending behavior**. The goal is to identify natural groupings within the customer base that reveal meaningful behavioral patterns.

## Success Criteria
The project is considered successful if the clustering model identifies **clear and interpretable customer segments** that can help businesses:

- Identify high-value customers
- Understand customer spending behavior
- Support targeted marketing campaigns
- Improve customer engagement and retention


## Dataset
The dataset contains the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

These variables are used to analyze purchasing patterns and identify groups of customers with similar behavior.

## Methodology

The project followed these key steps:

1. Data Exploration (EDA)
2. Data Preprocessing
3. Feature Selection
4. Feature Scaling using StandardScaler
5. Determining optimal clusters using the Elbow Method
6. K-Means Clustering
7. Visualization of customer segments

## Results

The clustering model identified **three distinct customer segments**:

- High spending customers
- Moderate spending customers
- Low spending customers

These segments can help businesses design targeted marketing strategies and improve customer engagement.

## Ethical Considerations

Although this project uses unsupervised learning and does not make automated decisions about individuals, it is important to consider potential biases in the data and model outputs.

The dataset includes demographic attributes such as **age and gender**, which may influence clustering outcomes. If these variables are not carefully interpreted, segmentation results could unintentionally reinforce stereotypes or lead to unfair marketing practices.

To mitigate this risk, the model should be used as a **decision-support tool rather than an automated decision-making system**. Businesses should combine clustering insights with human judgment and domain expertise.

Future improvements could include:

- Auditing cluster distributions across demographic groups
- Evaluating fairness across gender or age segments
- Testing alternative clustering algorithms
- Monitoring model performance on updated datasets

## Limitations & Future Work

While the K-Means clustering model successfully identifies customer segments, several limitations should be considered.

First, the dataset is relatively small and contains only a few variables. Important factors such as purchase frequency, product categories, or customer lifetime value are not included, which may limit the depth of segmentation insights.

Second, K-Means assumes that clusters are spherical and evenly distributed, which may not always represent real-world customer behavior patterns.

Future improvements could include:

- Incorporating additional behavioral features such as purchase history
- Testing other clustering algorithms such as DBSCAN or Hierarchical Clustering
- Applying dimensionality reduction techniques such as PCA
- Deploying the model in a business dashboard for real-time insights


## Tools Used

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

## Project Structure

```
customer-segmentation-capstone
│
├── Mall_Customers.csv
├── customer_segmentation.ipynb
├── README.md
└── requirements.txt
```

## Author

Eyda Duran  
Postgraduate Diploma in Artificial Intelligence & Machine Learning
