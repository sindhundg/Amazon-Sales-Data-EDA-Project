# Amazon-Sales-Data-EDA-Project
This project conducts an exploratory data analysis (EDA) on Amazon sales data to uncover key insights and trends regarding customer preferences and order fulfillment. The analysis involves data cleaning, visualization, and interpretation of various metrics that provide a comprehensive view of the sales landscape.

## Objectives

**Data Cleaning:** Prepare the dataset for analysis by handling missing values, renaming columns, and ensuring correct data types.

**Exploratory Analysis:** Visualize the data to identify trends, customer behaviors, and sales patterns across different categories and sizes.


## Data Cleaning Tasks

Data cleaning is a crucial step in preparing the dataset for analysis. This process involved identifying and addressing issues such as irrelevant or missing data, ensuring that the dataset is complete and ready for meaningful insights. The following tasks were performed to enhance data quality:

1. Dropped irrelevant or blank columns.

2. Checked for null values and calculated the total count of nulls.

3. Deleted rows with null values to ensure data integrity.

4. Changed data types for appropriate analysis.

5. Renamed columns for clarity and consistency.

6. Formatted float values for uniformity.

7. Generated descriptive statistics for specific columns to summarize data.


## Exploratory Analysis

### 1. Size Distribution:

A count plot was generated to analyze the distribution of product sizes purchased by customers. The analysis revealed that the M-size category was the most popular among buyers, indicating a strong preference for medium-sized products. This insight could inform inventory decisions and marketing strategies targeting size preferences.

![image](https://github.com/user-attachments/assets/0ee478b8-77d4-4556-b2d4-d2fee0795676)


### 2.Courier Status:

By examining the courier status of the orders, it was found that a significant majority of the orders are shipped via couriers. This finding highlights the efficiency of courier services in fulfilling customer orders and may suggest that improving relationships with courier partners could further enhance customer satisfaction and delivery times.

![Courier](https://github.com/user-attachments/assets/5d7bc277-d62d-446a-a88f-d521e5557499)


### 3. Sales by Category:

A histogram was created to visualize sales distribution across different product categories. The analysis indicated that T-shirts are the top-selling category, showcasing their popularity among consumers. Understanding category performance is crucial for inventory management and targeted marketing campaigns.

![T-shirts](https://github.com/user-attachments/assets/0042f3da-f3f1-4955-a466-5ec496af825f)


### 4. Buyer Type Analysis:

A pie chart was generated to distinguish between B2B (business-to-business) and retail buyers. The results indicated that a staggering 99.2% of purchases were made by retail buyers, compared to just 0.8% by B2B buyers. This insight underscores the dominance of retail transactions in the sales data and could influence future sales strategies.

![Pie_chart](https://github.com/user-attachments/assets/07ea1e87-dedd-460f-b079-3b7ee84c5cc6)


### 5. Size Availability by Category:

A scatter plot was used to explore the relationship between product categories and their available sizes. This analysis showed how sizes are distributed across different categories, which can inform decisions regarding product range and size availability to better meet customer demand.

![ScatterPlot](https://github.com/user-attachments/assets/8179e017-882a-4f71-b41d-9bb738e35605)


### 6. Geographical Insights:

The ship-state column was analyzed using a count plot to identify the distribution of buyers by state. The results indicated that Maharashtra had the highest number of buyers, suggesting it as a key market for targeted marketing efforts and localized promotions.

![State](https://github.com/user-attachments/assets/8610ad87-89e7-46d7-a6d3-a2153f7ebb60)


## Conclusion
The analysis provides valuable insights into consumer preferences and purchasing behavior on Amazon. Key findings reveal a strong preference for M-size products and indicate that retail buyers significantly outnumber B2B buyers. These insights can guide future marketing strategies and inventory management.


## Technologies Used
#### Python
#### Pandas
#### Matplotlib
#### Seaborn


## Future Work

Potential future analyses could include time-series analysis to understand seasonal trends, as well as sentiment analysis on customer reviews to further explore buyer satisfaction.


