# 🎮 Video Game Sales Data Analysis

This project analyzes video game sales data using Python and Jupyter Notebook. It focuses on cleaning the dataset, fixing inconsistent or missing values, and visualizing trends in sales performance across regions and platforms.

## 📁 Files

- `VideoGameYoutubeProject.ipynb` — Main notebook containing the full analysis and visualizations.
- `VideoGamesSales.csv` — Dataset containing sales, platform, country, region, and profit data.

## 📊 Project Highlights

- Dropped duplicate entries
- Handled null values in key columns like `Publisher`, `Region`, and `NA_Sales`
- Converted sales data from string to numeric format
- Standardized country names (e.g., "USA" to "United States")
- Renamed and restructured columns for clarity
- Detected outliers using the 95th percentile of National Sales

## 📈 Visualizations Included

| Chart Type   | Description |
|--------------|-------------|
| **Bar Chart**  | Total National Sales by Region and Country |
| **Box Plot**   | National Sales distribution by Country and Genre |
| **Pie Chart** | Share of National and Global Sales by Country |
| **Line Chart** | National and Global Sales trends over the years |

## 📊 Visualizations

### Bar Chart: National Sales by Region and Country
![Bar Chart](bar_chart.png)

### Box Plot: National Sales by Country and Genre
![Box Plot](box_plot.png)

### Pie Chart: Share of National and Global Sales by Country
![Box Plot](pie_chart.png)

### Line Chart: National and Global Sales Trends
![Line Chart](line_chart.png)









