# Superstore EDA (Exploratory Data Analysis)

This repository contains exploratory data analysis (EDA) performed on the Superstore dataset obtained from Kaggle. The Superstore dataset is a comprehensive collection of sales data from an online retailer and contains information about orders, customers, products, and sales.

## Dataset Information

The Superstore dataset comprises the following columns:

- **Order ID**: Unique identifier for each order.
- **Order Date**: Date when the order was placed.
- **Ship Date**: Date when the order was shipped.
- **Ship Mode**: Mode of shipment (e.g., first class, second class, standard class).
- **Customer ID**: Unique identifier for each customer.
- **Customer Name**: Name of the customer.
- **Segment**: Segment to which the customer belongs (e.g., consumer, home office, corporate).
- **Country**: Country where the order was placed.
- **City**: City where the order was placed.
- **State**: State where the order was placed.
- **Postal Code**: Postal code of the delivery address.
- **Region**: Region where the order was placed (e.g., South, West, Central, East).
- **Product ID**: Unique identifier for each product.
- **Category**: Category of the product (e.g., furniture, office supplies, technology).
- **Sub-Category**: Sub-category of the product (e.g., chairs, phones, binders).
- **Product Name**: Name of the product.
- **Sales**: Total sales amount for the order.
- **Quantity**: Quantity of the product ordered.
- **Discount**: Discount applied to the order.
- **Profit**: Profit generated from the order.

## Analysis Overview

The analysis was conducted using Python and included the following steps:

1. **Data Cleaning**:
   - Removed duplicates and null values.
   - Dropped unnecessary columns that were not relevant to the analysis.

2. **Basic Statistics**:
   - Identified the most popular categories and shipment modes based on frequency counts.
   - Calculated summary statistics to understand the distribution of sales, quantity, discount, and profit.

3. **Profit Analysis**:
   - Investigated profitability across different regions and specific states.
   - Focused on Texas as it exhibited significant profit loss.
   - Discovered that Texas offered the highest discounts compared to other states, resulting in decreased profits.

## Visualizations

The analysis includes various visualizations to better understand the dataset and the insights gained from it. Some of the visualizations created include:

- Histograms to visualize the distribution of numerical variables such as sales, quantity, discount, and profit.
- Bar charts to compare the frequency of different categories and shipment modes.
- Scatter plots to explore relationships between variables such as profit and discount.

## Conclusion

The analysis provided valuable insights into the Superstore dataset, particularly highlighting the impact of discounts on profitability. The findings can help stakeholders make informed decisions to optimize pricing and improve profitability, especially in regions like Texas where profit loss is significant.

Feel free to explore the Jupyter Notebook provided in this repository for more detailed analysis and code implementation.

