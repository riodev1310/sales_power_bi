# 1) Data model
Import all tables with appropriate data types.
Create A Calendar Table using DAX, focusing only on relevant dates.
Check relationships between tables, missing ones were added, ensuring proper table linkage and filtering.

# 2) Creating measures
Sales Measures Table: Created and organized for clarity.
Count of Orders: Calculates the total number of orders.
Revenue Total: Dynamically calculates total revenue using UnitPrice, Quantity, and Discount.
AOV (Average Order Value): Utilizes the previous measures to provide the average value per order.

# 3) Visualization
Cards: Visualized the calculated measures (Count of Orders, Revenue Total, AOV).
Revenue by Date: Added a line chart with improved readability using the Calendar Table.
Map: Showed the number of orders by territory.
Employee Table: Displayed full employee data, including Revenue Total and AOV with data bars.
Date Slicer: Added and configured a slicer based on the Calendar Table.

# 4) Quick measures
Revenue YTD: Successfully calculated using Quick Measures.
Revenue YoY %: Created and visualized for comparison across years.
Revenue New/Old Customers: Measures created for segmenting customer revenue.
Visualizations:
+ Line and column charts for YTD and YoY metrics.
+ Stacked area chart for New vs. Old Customer revenue distribution.

# 5) Tooltips
Revenue Tooltip Page:
+ Displays Revenue distribution (New vs. Old customers), Total Revenue, and Current Date.
+ Linked to the "Revenue by Date" visual.
Employee Tooltip Page:
+ Displays Employee's photo, name, and key metrics.
+ Linked to the Employee Table visual.
