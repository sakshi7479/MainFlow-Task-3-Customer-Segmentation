# MainFlow Task 3: Customer Segmentation using K-Means Clustering

**Objective**  
Performed customer segmentation using K-Means clustering based on Age, Annual Income, and Spending Score to help businesses target customers effectively.

**Dataset**  
- 200 customers from `customer_data.csv`  
- Features: Age, Annual Income (k$), Spending Score (1-100)

**Methodology**  
- Data Preprocessing & Standardization  
- Elbow Method + Silhouette Score → Optimal clusters = 5  
- Applied K-Means Clustering  
- Visualizations created (saved as PNG files)

**Results - 5 Customer Segments**

| Cluster | Size | Avg Age | Avg Income | Avg Spending | Segment Name              |
|---------|------|---------|------------|--------------|---------------------------|
| 0       | 58   | 55.3    | $47.6K     | 41.7         | Senior Standard           |
| 1       | 40   | 32.9    | $86.1K     | 81.5         | Premium High Spenders     |
| 2       | 26   | 25.8    | $26.1K     | 74.9         | Young Impulse Buyers      |
| 3       | 45   | 26.7    | $54.3K     | 40.9         | Young Balanced            |
| 4       | 31   | 44.4    | $89.8K     | 18.5         | High-Income Cautious      |

**Business Recommendations**  
- **Cluster 1**: Loyalty programs & premium products (Highest ROI)  
- **Cluster 4**: Personalized offers to increase spending  
- **Cluster 2**: Flash sales & social media campaigns  

**Deliverables**  
- `clustered_customer_data.csv` (with Cluster labels)  
- All visualizations (Elbow, 2D Scatter, PCA, Pairplot)  
- Professional Report (`Task_3_Customer_Segmentation_Report.pdf`)

**Tech Stack**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn, PCA

**Prepared by**: Sakshi  
**Submitted for**: MainFlow Task 3
