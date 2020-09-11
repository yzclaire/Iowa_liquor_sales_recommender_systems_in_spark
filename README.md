# Iowa_liquor_sales_recommender_systems_in_spark

### Project Objective
Build recommender systems for Iowa liquor sales in Spark (to identify cross-selling opportunity)

See Spark code in Jupyter Notebook [here](https://yzclaire.github.io/Iowa_liquor_sales_recommender_systems_in_spark/)

### Data Overview:

Iowa Liquor Sales Dataset([link](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy))

The dataset contains alcoholic purchases by liquor stores registered with the Iowa Department of Commerce that were logged in the Commerce department system from January 1, 2012 to current.

* Size of Dataset: 5GB
* Start Date: 2012-01-01
* Update Frequency: Monthly
* Row Count: 18,532,158
* Variables: Invoice ID, Store Name, Address, County, Item ID, Sales(Dollars), Volume Sold (Liters), Sales (Gallons) etc.
 
### Technique and Library 

Method : Collaborative Filtering

PySpark MLlib: Alternating Least Squares (ALS) algorithm


### Recommender Systems built
1. ALS with Explicit preferences (custom rating)
2. ALS with Implicit feedback (percentage of total order cost)
3. Fine tune ALS-Implicit feedback with Cross-validation
 
