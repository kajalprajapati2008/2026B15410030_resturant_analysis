 # Restaurant Data Analysis Using Python

## Project Overview

This project analyzes restaurant order data using **Python, Pandas, and
NumPy**. It explores sales performance, popular dishes, cuisine
preferences, ordering patterns, and delivery-mode performance.

The analysis is performed in Google Colab using
`22_restaurant_orders.csv`.

## Project Objectives

-   Explore the restaurant order dataset.
-   Calculate total and average revenue.
-   Identify popular dishes  
-   Compare restaurant performance.
-   Analyze cuisine and food-category performance.
-   Compare delivery modes.


## Dataset Information

-   **File:** `22_restaurant_orders.csv`
-   **Rows:** 862
-   **Columns:** 10

  Column              Description
  ------------------- --------------------------------
  `Order_ID`          Order identifier
  `Order_Date`        Date of the order
  `Restaurant_Name`   Restaurant name
  `Cuisine`           Cuisine type
  `Dish_Name`         Name of the dish
  `Category`          Food category
  `Quantity`          Quantity ordered
  `Unit_Price`        Price per unit
  `Order_Hour`        Hour when the order was placed
  `Delivery_Mode`     Order/delivery mode

## Technologies Used

-   **Python**
-   **Pandas** -- loading, exploring, grouping, and analyzing data.
-   **NumPy** -- numerical and statistical calculations.
-   **Google Colab** -- running the notebook.


## Analysis Performed

### 1. Basic Data Exploration

-   View the first and last records.
-   Check dataset dimensions and column names.
-   Inspect data types and statistical summaries.
-   Count unique values and check missing values.

### 2. Sales Analysis

-   Calculate row-level revenue using quantity multiplied by unit price.
-   Calculate total and average revenue.
-   Find maximum and minimum revenue.
-   Identify the record with the highest revenue.


### 3. Menu Analysis

-   Count records for each dish.
-   Identify popular dishes.
-   Calculate quantity sold and revenue by dish.
-   Calculate average unit price by dish.

### 4. Restaurant Analysis

-   Compare order counts across restaurants.
-   Calculate restaurant-wise revenue, quantity, and average revenue.


### 5. Cuisine Analysis

-   Compare cuisine popularity.
-   Calculate revenue 


### 6. Category Analysis

-   Compare order counts and quantity by category.
-   Calculate category-wise revenue.
 
### 7. Delivery Analysis

-  Display delivery mode


## How to Run the Project

1.  Download or clone this repository.
2.  Open the notebook in Google Colab.
3.  Upload `22_restaurant_orders.csv` to the Colab session.
4.  Ensure the CSV path in the notebook matches the uploaded file
    location.
5.  Run the notebook cells from top to bottom, or select **Runtime → Run
    all**.

## Revenue Calculation

Revenue is calculated as:

`Revenue = Quantity × Unit_Price`

The notebook creates this column from the existing dataset columns.


## Project Structure

``` text
restaurant-data-analysis/
|── dataset
|   |── 22_restaurant_orders.csv
├──  README.md
├── restaurant_analysis.ipynb

```


## Conclusion

This project demonstrates how Pandas and NumPy can be used to explore
and analyze restaurant order data. It provides practice with DataFrames,
grouping, aggregation, sorting.