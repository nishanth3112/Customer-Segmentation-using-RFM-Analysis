# Customer Segmentation using RFM Analysis

This project involves analyzing e-commerce customer data using RFM (Recency, Frequency, Monetary) analysis to identify customer segments. The goal is to provide actionable insights for improving marketing strategies, customer retention, and revenue generation.

## Dataset

### E-commerce Data
- **Description**: A dataset containing transactional records from an e-commerce platform, sourced from Kaggle.  
- **Focus**:
  - Includes customer purchase data, such as invoice numbers, product quantities, purchase dates, and total prices.  
  - Allows for the calculation of key metrics to segment customers based on purchasing behavior.  
- **Applications**: Used to identify high-value customers, dormant accounts, and purchasing trends for personalized marketing strategies.  
- **Key Features**:
  - Transactional data, including customer IDs, product descriptions, and purchase details.  
  - Comprehensive for exploring customer segmentation and behavioral trends.  

- **Link to the Dataset**: [E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

## Significance in the Project
- **Data Preprocessing**: Cleaned and standardized the dataset by handling missing values, removing duplicates, and ensuring consistency.  
- **RFM Metric Calculation**:
  - **Recency**: Measured days since the last purchase.  
  - **Frequency**: Counted total purchases per customer.  
  - **Monetary**: Calculated total spending by each customer.  
- **Customer Segmentation**: Grouped customers into actionable segments using K-Means clustering, with optimal cluster determination via the elbow method.  
- **Insights and Visualization**: 
  - Identified key customer groups such as high-value customers, recent but infrequent buyers, and dormant accounts.  
  - Created visualizations including bar charts, scatter plots, and heatmaps for detailed analysis.  
- **Marketing Recommendations**: Designed personalized strategies for different segments, such as loyalty programs for high-value customers and re-engagement campaigns for dormant ones.

This project highlights the importance of RFM analysis in understanding customer behavior, optimizing marketing strategies, and driving business growth.
