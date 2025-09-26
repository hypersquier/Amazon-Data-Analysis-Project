# Amazon Data Analysis Project

## Overview
This project provides a deep and comprehensive analysis of Amazon product data, focusing on understanding the relationship between pricing (discounts) and product quality (ratings). We used advanced features in Microsoft Excel (Pivot Tables, Power Query, and custom formulas) to transform raw data into a dynamic dashboard that delivers actionable business insights.

## Features
- Data cleaning and preprocessing
- Exploratory data analysis 
- Visualization 
- Statistical analysis and summary reports

## Technologies Used
- Microsoft Excel: Primary platform for analysis, calculation, and visualization.
- Power Query: Data cleaning and structuring, including removing currency symbols, converting text columns to numbers, and splitting the complex category column into granular subcategories.
- Pivot Tables: Data aggregation, calculating average rating per discount range, and creating dynamic groups for discount_percentage.
- XLOOKUP: Efficiently retrieving product names corresponding to the absolute highest and lowest rating values.
- Custom Formulas (IF/IFS): Categorizing discount percentages into defined ranges (e.g., "20%-30%") for easier analysis.
- Scatter Plot: Visualizing the correlation between the numerical variables (discount_percentage and rating).

## Key Performance Indicator (KPI)
- **Total Sum (Actual Price):** The total original value of the products analyzed (before discounts). This gives context to the overall market value of the inventory.
- **Average Discount Percentage:** The average discount offered across all products. Used to gauge the aggressiveness of the pricing strategy.
- **Average Rating:** The overall average rating of all products. A quick and effective metric for general product quality.
- **Highest Rating Product:** The name of the product with the highest rating (5.0). Essential for identifying top-performing, high-quality inventory.
- **Lowest Rating Product:** The name of the product with the lowest rating. Used to flag products requiring immediate review or removal due to poor customer feedback.

## Usage
- /data

- Open the main Excel analysis file and follow the steps in each sheet to clean, explore, and visualize the data.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements.

## License
This project is licensed under the MIT License.

## Contact
For questions or collaboration, please contact [zarab99999@gmail.com].
