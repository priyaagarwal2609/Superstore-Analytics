# Superstore Analytics Dashboard

## Overview

The Superstore Analytics Dashboard provides a comprehensive overview of the store's performance across different categories and time frames. It helps the regional managers to understand their customers better. Here's a detailed summary based on the provided dashboard:

#### Role-level Security

A dynamic role-level security model has been implemented to restrict data visibility within the dashboard. This ensures that managers only see data pertinent to their assigned territories. Additionally, an admin role has been created with access to data across all regions.

![image](https://github.com/user-attachments/assets/d18219f5-867d-460c-820a-29ed141b45d0)


### 1) SUMMARY PAGE

The summary page consolidates high-level KPI information, allowing managers to view critical metrics at a glance. These metrics are filtered based on the selected period and values in the slicers (Year, Customer Type, Product Type, Location, Month, Quarter).

![image](https://github.com/user-attachments/assets/a2eaa665-1085-470b-9f1f-8d27be69b61c)

#### Key Metrics:

Total Sales: 
Reflects the overall sales amount with year-over-year percentage change.

Total Profit: 
Indicates the total profit with year-over-year percentage change.

Orders Placed: 
Shows the number of orders placed with year-over-year percentage change.

Returned Orders: 
Displays the number of returned orders with year-over-year percentage change.

Average Shipping Days: 
Indicates the average number of days taken to ship orders.

It also includes pie charts to visualize contributions from different customer/product categories.

![image](https://github.com/user-attachments/assets/68b50289-4e05-49e4-8a33-355e889dfeb5)

#### Sales, Profit, and Orders breakdown at Month & Quarter level:

Below line graphs are broken down at both monthly and quarterly levels.

Field parameters allow dynamic axis changes based on the Month/Year slicer selection, enabling managers to compare current year data (green line) against the previous year (blue line).

![image](https://github.com/user-attachments/assets/c95c93bf-e21f-4ce4-8ae0-3a37db544861)

#### Sales by State:

A combined view of Table and Map visual, created via bookmarks. 

Shape Map shows state/province wise data in the visual.Darker shades indicate higher sales, while lighter shades indicate lower sales.Conditional formatting highlights sales amounts across different U.S. regions.

![image](https://github.com/user-attachments/assets/450c43ad-d9fb-48af-b514-cce9d1488ead)


Table shows last year's sales percentage values in red to indicate negative sales data.

![image](https://github.com/user-attachments/assets/41e749ad-2dde-4747-b76d-ef966040b335)

#### Top 10 bar graph for "Cities", "Products", "Customers" by Sales, Quantity, Profit:

Displays the top 10 categories by Sales, Quantity, and Profit for "Cities", "Products", and "Customers".

These graphs assist in identifying top performers, aiding managers in making informed business decisions to retain high-performing entities.

![image](https://github.com/user-attachments/assets/7f17fb90-717f-434a-b551-023ac0ec2a26)

#### Slicer Pane:

![image](https://github.com/user-attachments/assets/8010bf31-15c6-480d-b6ce-3793e754f86a)

### 2) PRODUCT PAGE

![image](https://github.com/user-attachments/assets/01d0bc86-bcde-44bc-a51a-ac4c48214e94)

![image](https://github.com/user-attachments/assets/8ee3eda3-d775-4cf2-8724-94f7b2bfd33e)

This page provides a detailed analysis of product performance across various categories and sub-categories, offering valuable insights for regional managers.

Key Segments and Visualizations:

#### Top and Bottom Performers

Objective: 
Identify top-performing and least-performing products by sales and profit for the selected period.

Purpose: 
Assist regional managers in sustaining top performers and strategizing actions to boost sales and profit for underperforming products.
Decomposition Tree Chart

Functionality: Segregates profit and sales data by region, category, and sub-category.
Features: Utilizes field parameters for dynamic slicer creation. Bar colors adjust based on category selection, providing a clear visual representation of the data hierarchy.

#### Map Visual

Objective: Display regional sales performance.

Details:
Bubble Size: Represents sales amount.
Highest Sales: Highlighted by "California" (blue bubble).

Lowest Sales: Highlighted by "Columbia".
Purpose: Offer a quick geographic overview of sales distribution.

#### Line and Custom Column Chart

Objective: Depict monthly sales and profit margins.

Features: Combines line and column charts to provide a comprehensive view of trends over time.

#### Top Product by Sales

Functionality: Employs a rank slicer to dynamically update top and bottom product values based on sales.
Features: Uses both field and numeric parameters for flexible visualization.

![image](https://github.com/user-attachments/assets/4188b175-a89f-4133-ae1b-9cc436aec685)


![image](https://github.com/user-attachments/assets/6281c247-59a6-4bcb-b431-19860eccacb1)

### 2) CONSUMER PAGE

Small mutiple graph is used to show total customer by Region which can be slice and dice at segemnt, category and sub-category. 

In a single view, users can compare data for all the region.

![image](https://github.com/user-attachments/assets/f925560b-694d-4ef3-ae59-d039d274bb15)


### 2) CUSTOMER LIFETIME VALUE (CLV) PAGE
![image](https://github.com/user-attachments/assets/db792b25-d253-47b1-873f-0337925841cc)
