
# IMDb Data Analysis Project

This project is part of my portfolio to showcase my skills in data analysis and visualization using Python. The notebook `imdb.ipynb` contains a detailed analysis of an IMDb dataset, focusing on the exploration of movie ratings, genres, and other factors.

## Dataset

The dataset used in this analysis comes from IMDb and contains various attributes such as:
- Movie titles
- Year of release
- Ratings
- Number of votes
- Genre information

This dataset provides a rich source of information for analyzing trends and relationships in the movie industry.

## Objectives

The main goals of this project are:
1. **Data Cleaning and Preprocessing:** Handle missing data, clean column values, and prepare the dataset for analysis.
2. **Exploratory Data Analysis (EDA):** Gain insights into the distribution of movie ratings, the popularity of different genres, and trends over time.
3. **Data Visualization:** Use visual techniques to better understand the data and communicate findings.
4. **Statistical Insights:** Derive statistical observations regarding the ratings, genres, and correlations between different variables.

## Steps of Analysis

1. **Loading the Dataset:** The dataset is imported and inspected for missing values and inconsistencies.
2. **Data Cleaning:** Rows with missing or incorrect data are addressed. For example, non-numeric data in rating columns is handled, and genres are processed for multi-label entries.
3. **Exploratory Data Analysis:** 
    - **Rating Distribution:** Visualize the distribution of IMDb ratings.
    - **Genres Analysis:** Analyze which genres are most common and how their ratings differ.
    - **Year-wise Analysis:** Observe trends in movie production and rating evolution over time.
4. **Correlation Analysis:** Look at correlations between number of votes and ratings, as well as other interesting variables.
5. **Visualizations:** Throughout the notebook, various plots such as histograms, bar plots, and scatter plots are used to illustrate key points.

## Results

Some key findings from this analysis:
- The distribution of IMDb ratings shows a tendency towards higher ratings, with fewer movies receiving very low or very high scores.
- Certain genres such as Drama and Action are more prevalent in the dataset, while others like Horror or Documentary have more niche audiences.
- There is a moderate correlation between the number of votes a movie receives and its average rating.

## Installation and Usage

To run this notebook, you will need the following libraries:
- pandas
- numpy
- matplotlib
- seaborn

To set up the environment and run the analysis:
1. Clone the repository.
   ```bash
   git clone https://github.com/yourusername/imdb-data-analysis.git
   ```
2. Install the required packages.
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run the cells to reproduce the analysis.
   ```bash
   jupyter notebook imdb.ipynb
   ```

## Conclusion

This project highlights my ability to work with real-world datasets, clean and preprocess data, and perform exploratory data analysis to gain insights into movie trends. The visualizations and statistical findings provide a comprehensive overview of IMDb data.
