# ML Developer Case Study - Utku Özkan

![CRISP](https://github.com/utkuuozkann/ML-Developer-Case-Study-Utku-Ozkan/blob/main/ML%20Developer%20Case%20Study%20-Utku%20%C3%96zkan/CRISP.png)
## Business Understanding

*Customer segmentation of a shopping site's data with RFM analysis and Clustering analysis*

## Data Understanding

*The data set includes order information from December 2010 to December 2011.*

You can find the dataset used in the project [here](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset)

Column Names: 
 - InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

 - StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

 - Description: Product (item) name. Nominal.

 - Quantity: The quantities of each product (item) per transaction. Numeric.

 - InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.

 - UnitPrice: Unit price. Numeric, Product price per unit in sterling.

 - Customer ID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

 - Country: Country name. Nominal, the name of the country where each customer resides.


## Data Preparation

*Negative values were excluded from the dataset due to returned items in the dataset.*

*A total price column was created to find the monetary value.*


## Modeling

### RFM Analysis

*RFM Metrics Calculated*

Description of RFM Metrics: 

1)Recency: How recently has the customer made a transaction with us ? 

2)Frequency: How frequent is the customer in ordering/buying some product from us ?

3)Monetary: How much does the customer spend on purchasing products from us ?


*Segments were created according to the RFM Score.*


### Clustering Analysis


1) *Values ​​Normalized*
2) *Calculated the optimum number of clusters with 'The Elbow method'*
3) *Calculated the optimal number of clusters with 'silhouette_score'* 
4) *Did Fitting process for clustering*

## Evaluation

*Appropriate actions were evaluated for customers divided into groups by RFM analysis and Cluster Analysis.*
