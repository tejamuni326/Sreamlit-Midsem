
# IMDb Movie Analytics Dashboard

## Project Description
The IMDb Movie Analytics Dashboard is a Python-based interactive web application developed using Streamlit. It is used to explore, analyze and visualize the Top 250 Movies on IMDb dataset.

## Objectives
- To load and explore the IMDb movie dataset.
- To calculate important movie statistics.
- To visualize movie ratings, genres and worldwide gross collections.
- To provide interactive movie filtering and searching.
- To implement session state and form handling.

## Features

### 1. Dataset Loading
- Load CSV dataset using Pandas.
- Display first 10 records.
- Display rows, columns and data types.
- Check missing values.

### 2. KPI Metrics
- Total number of movies.
- Average IMDb rating.
- Highest IMDb rating.
- Total number of votes.

### 3. Data Visualization
- Movies by Genre – Bar Chart.
- IMDb Rating Distribution – Histogram.
- Rating vs Number of Votes – Scatter Plot.
- Top 10 Movies by Worldwide Gross – Bar Chart.

### 4. Interactive Movie Explorer
- Genre selection.
- Country selection.
- IMDb rating filter.
- Minimum votes filter.
- Movie title search.
- Sorting by IMDb rating.
- Display filtered movie records.

### 5. Movie Search
- Search movies by title.
- Select preferred genre.
- Set minimum IMDb rating.
- Display movie details.
- Use Streamlit Session State.

## Technologies Used
- Python
- Streamlit
- Pandas
- Plotly

## Dataset
IMDb Top 250 Movies Dataset (2026).

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## How to Run

Run the following command in the VS Code terminal:

```bash
streamlit run app.py
```

## Project Files

- app.py – Main Python application.
- imdb_top_250.csv – Dataset.
- requirements.txt – Required Python libraries.
- README.md – Project documentation.

## Conclusion
The IMDb Movie Analytics Dashboard provides an interactive platform to analyze and explore movie information. It uses data visualization, filtering and searching techniques to make movie data analysis simple and effective.
