# Netflix Data Analysis and Visualization

##  Project Overview
This project involves a comprehensive analysis of the Netflix dataset to understand the content strategy, trends, and distribution of movies and TV shows available on the platform. The analysis is performed using Python in a Jupyter Notebook, leveraging libraries like Pandas for data manipulation and Matplotlib/Seaborn for visualization.

##  Dataset
The dataset `netflix1.csv` contains information about movies and TV shows added to Netflix, including:
- **Show ID**: Unique ID for every movie/show
- **Type**: Identifier - Movie or TV Show
- **Title**: Title of the movie/show
- **Director**: Director of the content
- **Cast**: Actors involved
- **Country**: Country of production
- **Date Added**: Date it was added to Netflix
- **Release Year**: Actual release year
- **Rating**: Content rating (TV-MA, PG-13, etc.)
- **Duration**: Total duration
- **Listed In**: Genre
- **Description**: Summary description

##  Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data cleaning, manipulation, and feature engineering.
- **Matplotlib & Seaborn**: For creating static visualizations.
- **Jupyter Notebook**: For interactive analysis and reporting.

##  Key Analysis & Insights
1.  **Content Distribution**: Identified the ratio between Movies and TV Shows, showing a dominance of Movies.
2.  **Trend Analysis**: Analyzed the volume of content added over the years, highlighting peak periods of growth around 2018-2020.
3.  **Genre Analysis**: Uncovered top genres, with **International Movies**, **Dramas**, and **Comedies** leading the platform.
4.  **Director Insights**: Highlighted top content creators, noting prolific directors like Rajiv Chilaka.
5.  **Duration Trends**:
    - Movies: Most fall within the 80-120 minute range.
    - TV Shows: The vast majority are single-season series.
6.  **Temporal Patterns**: Heatmap analysis revealed seasonal trends in content addition.

##  How to Run
1.  Ensure you have Python installed with the necessary libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
2.  Open `netflix_analysis.ipynb` in Jupyter Notebook or JupyterLab.
3.  Run the cells sequentially to reproduce the analysis and visualizations.
