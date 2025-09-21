# Supermarket-Grocery-Sales-Tamilnadu
A) The Supermart Grocery Sales dataset contains daily customer transaction data for a store in a certain region from 2015-
2018. This dataset includes detailed records of every purchase made by customers over that four-year period

B) This data analysis project was developed using Python and leverages the following set of libraries:

**Data Processing**:
    
     Pandas: The primary library used for data cleaning, manipulation, and analysis.
    
     NumPy: Used to support efficient numerical operations on the dataset.

**Data Visualization**:
    
     Matplotlib & Seaborn: Used to generate various plots and visualizations that assist with Exploratory Data Analysis (EDA).

**Modeling & Metrics**:
    
     Scikit-learn: Used to implement Machine Learning algorithms. Specific modules used include:
    
         `KMeans` for customer segmentation.
         
         `StandardScaler` for data normalization.
         
         `silhouette_score` for evaluating the clustering model.

**Additional Functions**:
   
    *datetime*: Used for working with time-based data from the 'Order Date' column.

C) This dataset has 14 columns that contain information about:

1.  Order ID
2.  Customer Name
3.  Category
4.  Sub Category
5.  City
6.  Order Date
7.  Region
8.  Sales
9.  Discount
10. Profit
11. State
12. Total Sales
13. Total Orders
14. Cluster

D) This data is highly functional for analysis, such as:

1. Sales Analysis: Identifying top-selling products, total sales per branch, and daily or monthly sales trends.
2. Customer Analysis: Creating customer segmentation based on sales and purchase transactions.
3. Performance Analysis: Evaluating product categories that are frequently and rarely purchased by customers.

E) Insights:

**Customer Segmentation**

The analysis successfully identified 3 main customer segments:
- Cluster 1 (Lower-Spending Customers): Customers with the lowest average total sales ($279,642.00) and orders (186.57).
- Cluster 0 (Middle-Spending Customers): The largest segment with average total sales ($302,087.52) and orders (201.83) in the middle range.
- Cluster 2 (Higher-Spending Customers): The most valuable customer group with the highest total sales ($325,922.29) and orders (218.43).
