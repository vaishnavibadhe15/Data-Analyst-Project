# Pizza Sales Analysis 🍕📊

## Project Overview
This project explores pizza sales data using Python to understand sales performance, customer ordering patterns, and popular pizza products. The analysis is performed in a Jupyter Notebook using Pandas, NumPy, Matplotlib, Seaborn, and Plotly Express.

## Objectives
- Calculate key business metrics such as revenue, pizzas sold, total orders, average order value, and average pizzas per order.
- Identify the most frequently used pizza ingredients.
- Analyze orders and revenue by day of the week.
- Explore monthly order trends.
- Compare sales contribution by pizza category and pizza size.
- Identify the top-selling and lowest-selling pizzas.

## Tools & Libraries
- **Python**
- **Pandas** — data loading, cleaning, grouping, and analysis
- **NumPy** — numerical operations
- **Matplotlib** — charts and visualizations
- **Seaborn** — heatmap visualization
- **Plotly Express** — imported for interactive visualization

## Analysis Included
1. **Dataset overview** — inspect rows, columns, data types, and descriptive statistics.
2. **Key performance indicators (KPIs)** — total revenue, total pizzas sold, unique orders, average order value, and average pizzas per order.
3. **Ingredient analysis** — count the most common ingredients.
4. **Orders by weekday** — compare unique orders across the days of the week.
5. **Revenue by weekday** — compare total sales revenue by day.
6. **Monthly order trend** — visualize the number of unique orders by month.
7. **Sales by pizza category** — show each category's percentage contribution to sales.
8. **Sales by category and size** — use a heatmap to compare sales percentages.
9. **Best-selling pizzas** — examine pizzas by quantity sold and by unique orders.
10. **Lowest-selling pizzas** — identify pizzas with the lowest sales quantity.

## Dataset
The notebook expects a CSV file named `pizza_sales.csv` containing columns such as `order_id`, `order_date`, `quantity`, `total_price`, `pizza_ingredients`, `pizza_category`, `pizza_size`, and `pizza_name`.

**Note:** Add `pizza_sales.csv` to your repository (if you are allowed to share the dataset) or update the file path in the notebook to match your local setup. The current notebook uses `/content/pizza_sales.csv`, which is a Google Colab path.

## How to Run
1. Clone or download this repository.
2. Make sure `pizza_sales.csv` is available in the location expected by the notebook.
3. Open `pizza_seles_analyasis_project_ipnb.ipynb` in Jupyter Notebook or Google Colab.
4. Install the required libraries if needed:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

5. Run the notebook cells from top to bottom.

## Key Metrics
The notebook calculates:
- Total Revenue
- Total Pizzas Sold
- Total Orders
- Average Order Value
- Average Pizzas per Order

The exact results are generated when the notebook is run against the dataset.

## Project Structure
```text
.
├── pizza_seles_analyasis_project_ipnb.ipynb
├── pizza_sales.csv  # dataset, if included
└── README.md
```

## Conclusion
This analysis provides an overview of pizza sales performance and helps explore demand patterns across time, pizza categories, sizes, and individual products. The findings can support data-informed decisions about product focus and sales planning.

---
*Created as a Python data analysis project.*
