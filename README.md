# Revenue Increase Analysis of Maven Toys

Revenue increase analysis of Maven Toys Stores in Mexico for Q4 2018 using Python and Tableau.

# Introduction

Maven Toys is a prominent toy store located in Mexico. As of the end of Q3 2018, the store has encountered a decline in revenue compared to the previous quarter. To address this challenge, Maven Toys is striving to increase its revenue by the end of Q4. To facilitate this goal, an in-depth analysis of sales data from January 1, 2017, to September 30, 2018, is underway, focusing on identifying potential revenue growth opportunities for Q4 2018.

# **Data Overview**

This dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/toy-sales/data) and comprises over 829,262 transactions across all stores operated by Maven Toys, providing a robust foundation for analysis.

The dataset includes four tables, each containing essential information as follows:

### Inventory Table

| No | Column Name | Description | Range/Value |
| --- | --- | --- | --- |
| 1 | Store_ID | Store ID | Unique identifier for each store (PK) |
| 2 | Product_ID | Product ID | Unique identifier for each product (FK) |
| 3 | Stock_On_Hand | Quantity of product in stock (inventory) | Integer value representing stock quantity |

### Product Table

| No | Column Name | Description | Range/Value |
| --- | --- | --- | --- |
| 1 | Product_ID | Product ID | Unique identifier for each product (PK) |
| 2 | Product_Name | Product Name | Name of the product |
| 3 | Product_Category | Product Category | Category to which the product belongs |
| 4 | Product_Cost | Product Cost ($USD) | Decimal value representing product cost |
| 5 | Product_Price | Retail Price of Product ($USD) | Decimal value representing retail price |

### Sales Table

| No | Column Name | Description | Range/Value |
| --- | --- | --- | --- |
| 1 | Sale_ID | Sale ID | Unique identifier for each sale (PK) |
| 2 | Date | Transaction Date | Date when the sale occurred |
| 3 | Store_ID | Store ID | Unique identifier for each store (FK) |
| 4 | Product_ID | Product ID | Unique identifier for each product (FK) |
| 5 | Units | Number of Units Sold | Integer value representing the number sold |

### Stores Table

| No | Column Name | Description | Range/Value |
| --- | --- | --- | --- |
| 1 | Store_ID | Store ID | Unique identifier for each store (PK) |
| 2 | Store_Name | Store Name | Name of the store |
| 3 | Store_City | City in Mexico where the store is located | Name of the city |
| 4 | Store_Location | Location within the city where the store is found | Specific location within the city |
| 5 | Store_Open_Date | Date when the store opened | Date of the store's opening |

# Objectives

The main objectives of this analysis are:

- To assess the revenue performance of Maven Toys from Q3 2017 to Q4 2018.
- To identify key factors influencing revenue changes.
- To provide actionable recommendations for revenue growth in Q4 2018 and beyond.

# Methodology

The analysis encompasses data cleaning, exploration, analysis, and visualization using Python and Tableau. Key metrics, such as total revenue and trends in units sold, will be examined to derive valuable insights.

# Conclusion

Toy sales experienced a significant spike in Q4. The target revenue increase of 35% in Q4 2018 is achievable if Maven Toys optimizes its sales strategies, including efficient product stock management and targeted promotions.

# Recommendation

- **Segmented Discounts**: Implement discounts on best-selling products on December 24th and 31st at high-performing store locations. For stores with lower sales, offer smaller discounts to drive revenue.
- **Product Bundling**: Create product bundles that pair high-selling items with slower-moving products to increase the appeal and sales of less popular items.
- **Stock Optimization**: Monitor product stock levels in real-time. Increase stock for high-demand products and enable quick restocking to avoid stock shortages during peak periods.

# Acknowledgments

Special thanks to the contributors and data providers on Kaggle for making this analysis possible. Your efforts are greatly appreciated.
