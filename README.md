<h1 align="center">Analyzing Logistics Transactions in Looker Studio - Spreadsheet</h1>
 
  <img align="right" alt="coding" width="500" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWlnNjR6bGVtMGoyaDlweTBhMzdpN2VkeHdvMGVxYWtkdG51Mmd6eiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Xp2aMizmMYaMo/giphy.gif">
  
Looker Studio (formerly Google Data Studio) is a great tool for visualizing and exploring your logistics transaction data. Here's how you can get started:

### Data Upload

1. Upload your data containing the mentioned fields (Order ID, Order Date, etc.) into Looker Studio. You can connect to various data sources like Google Sheets directly.

### Building a Report:

2. Dimensions: Drag the following fields from the "Data" panel to the "Dimensions" area:

* Customer ID: This will allow you to segment your data by customer.
* Product Category: Group products by their categories for analysis.
* Ship Date (or Order Date): Analyze trends over time.
* Country (should be USA for your data): Filter or group by country (though not relevant in this case).
* City or State (optional): Add location-specific breakdowns (be mindful of privacy concerns).

3. Metrics: Drag the following fields to the "Metrics" area:

* Sales Quantity: Total quantity of products sold.
* Profit: Total profit earned.
* Discount: Total amount of discount applied.
* You can also calculate metrics like Average Profit per Order by using a formula: Sum(Profit) / Count(Order ID).

4. Visualizations:

* Bar Chart: Visualize total Sales Quantity or Profit by Customer, Product Category, or Ship Date (month/year).
* Geo Map (optional): If your data includes State, you can plot Sales Quantity or Profit on a US map (be cautious with privacy implications).
* Line Chart: See trends in Sales Quantity or Profit over time (Ship Date or Order Date).
* Pie Chart: Analyze the proportion of Sales Quantity or Profit by Product Category.

5. Filters: Add filters to focus on specific aspects. For example, filter by a specific date range, customer segment, or product category.

### Additional Features:

* Drill-Down: Allow users to click on a bar or segment to see more details. For instance, clicking on a Customer ID could reveal individual order details.
* Time Series Analysis: If your data includes timestamps for Order Date or Ship Date, you can use Looker Studio's time series features to analyze trends and seasonality.

By using these steps and features, you can create informative and interactive dashboards to gain insights into your logistics performance in the US. Remember to tailor the visualizations and analysis to your specific business goals and questions.

### Report View 🤖
```bash
https://lookerstudio.google.com/s/kR1qQgEl0EI
```

### Dataset
```bash
https://docs.google.com/spreadsheets/d/1auPNL-yln4aEuPZFmacbNaUJNROby8SLyYEbBSe5fiE/edit#gid=422745916
```
