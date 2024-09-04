# Climate Data Analysis

## Project Overview

This project analyzes climate data, particularly from Hawaii, to uncover trends and patterns in weather measurements. It utilizes Python, SQL, and data visualization tools to explore climate trends and answer specific research questions.

## File Descriptions

- **app.py**: A Flask API script that serves data and handles climate-related requests, including temperature and precipitation queries.
- **climate_starter.ipynb**: A Jupyter Notebook containing exploratory data analysis (EDA), visualizations, and SQL queries to analyze the climate data.
- **hawaii_measurements.csv**: A dataset of climate measurements (e.g., temperature, precipitation) from various stations in Hawaii.
- **hawaii_stations.csv**: A list of weather stations in Hawaii, including station ID, name, and location.
- **hawaii.sqlite**: An SQLite database storing climate measurements and station information for easy querying.


## How to Run the Code

### Running the Flask API

1. Ensure dependencies are installed.
2. Run the `app.py` script:
    ```bash
    python app.py
    ```
3. Access the API at `http://127.0.0.1:5000/`.

### Running the Jupyter Notebook

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open `climate_starter.ipynb` and execute the cells to perform the analysis.

## Dependencies

- Flask
- SQLAlchemy
- Pandas
- Numpy
- Matplotlib
- Jupyter Notebook

# Analysis

The analysis focuses on identifying trends in temperature and precipitation data from various Hawaiian stations to understand the region's climate behavior.

## Key Questions Addressed

- **Temperature Trends**: What are the average temperatures during different times of the year? How do these temperatures vary across different stations?
- **Precipitation Analysis**: What are the precipitation levels across different stations? Are there any significant trends or outliers?
- **Station Data Comparison**: How do various stations compare in terms of the data they provide? Are some stations more consistent or reliable than others?
## Results

- **Temperature Analysis**: The analysis reveals seasonal variations in temperature across the stations. We identified the warmest and coolest periods of the year, with clear trends indicating temperature peaks during the summer months.

- **Precipitation Patterns**: The data showed variability in precipitation levels across different stations. Some stations reported higher levels consistently, indicating regional differences in rainfall.

- **Station Comparisons**: By comparing data across stations, we identified which stations provided the most complete and reliable data sets. This is crucial for understanding localized climate conditions.

# Visualizations
The Jupyter Notebook includes various visualizations such as line charts, bar graphs, and scatter plots to illustrate the findings. These visualizations make it easier to understand trends and anomalies in the data.

# Usage Examples
## Flask API

- **Temperature Data**: Fetch temperature data for a specific date range.
- **Precipitation Data**: Query precipitation levels for specific stations.
# Jupyter Notebook

- **EDA and Visualization**: Perform data exploration and visualization.
- **SQL Queries**: Retrieve and analyze data directly from the SQLite database.



