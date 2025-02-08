# Electronic-market-sales
Steps Taken:
Merged Monthly Data: Combined multiple CSV files into a single DataFrame.
Handled Missing and Incorrect Data:
Removed missing values.
Cleared nonsensical date values.
Ensured proper date parsing.

Created Additional Columns:
Extracted month information from the Order Date.
Created a Sales column by multiplying Quantity Ordered and Price Each.
Extracted the city from the Purchase Address.

Aggregated Data:
Grouped by month to find total sales per month.
Grouped by city to determine which city had the highest sales.
Grouped by hour to identify the optimal time to run advertisements.

Analysis Results:
Best Month for Sales: December, with total sales of $4,613,443.34.
Top Selling City: San Francisco, with total sales of $8,262,203.91.
Best Time for Advertising: Between 11 AM and 7 PM, as these hours have peak sales activity.
