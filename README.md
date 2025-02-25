# Customer Behavior Analysis for Kira Plastinina

## 1. Defining the Data

The dataset includes **10 numerical** and **8 categorical attributes**. The `Revenue` attribute serves as the class label.

### Numerical Features:
- **Administrative**, **Administrative Duration**, **Informational**, **Informational Duration**, **Product Related**, and **Product Related Duration**:  
  Represent the number of different types of pages visited by the user in a session and the total time spent on each page category. These values are derived from the URL information of pages visited and updated in real time as users interact with the site.

- **Bounce Rate**: Percentage of visitors who enter the site from a specific page and leave without triggering further requests during that session.

- **Exit Rate**: Percentage of pageviews where the page was the last in a session.

- **Page Value**: Average value of a web page that a user visited before completing an e-commerce transaction.

- **Special Day**: Indicates proximity to a significant special day (e.g., Mother’s Day, Valentine’s Day) when transactions are more likely. The value is determined based on the duration between the order date and delivery date (e.g., Valentine’s Day ranges from February 2 to February 12, with a maximum value of 1 on February 8).

### Categorical Features:
- **Operating System**, **Browser**, **Region**, **Traffic Type**, **Visitor Type** (returning or new visitor), **Weekend** (Boolean indicating whether the visit occurred on a weekend), and **Month of the Year**.

## 2. Solution

To analyze customer behavior, we apply **unsupervised learning models** such as:
- K-means clustering
- Hierarchical clustering

## 3. Defining the Question

### Specifying the Question:
Enable **Kira Plastinina**, a Russian brand, to understand customer behavior from collected data and identify characteristics of different customer groups.

### Defining the Metric of Success:
Successfully identify key customer groups and their defining characteristics.

### Understanding the Context:
Kira Plastinina is a Russian brand sold through a now-defunct chain of retail stores in **Russia**, **China**, **Philippines**, **Ukraine**, **Kazakhstan**, **Belarus**, and **Armenia**.  
The insights from this analysis are intended to help the team formulate effective marketing and sales strategies for the brand.

## 4. Experimental Design

1. Problem Definition  
2. Data Sourcing  
3. Data Inspection  
4. Data Cleaning  
5. Exploratory Data Analysis (EDA)  
6. Implementing the Solution  
7. Challenging the Solution  
8. Follow-up Questions  

## 5. Conclusion

This analysis will provide actionable insights into customer behavior, enabling Kira Plastinina to understand its customer base better and optimize marketing efforts.

