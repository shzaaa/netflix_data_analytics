# netflix_data_analytics

## Project Overview
This project analyzes a Netflix dataset containing information about movies and series, including genres, ratings, country availability, languages, release dates, actors, directors, and more. The goal is to uncover insights about content quality, popularity, hidden gems, audience reach, and trends over time.

The project includes:
- Data cleaning and preprocessing
- Feature engineering (e.g., country & language count, hidden gem flag)
- Exploratory Data Analysis (EDA) with charts and distributions
- Insights for content strategy and audience preferences


## Dataset
- The dataset contains columns such as: `Title`, `Genre`, `Languages`, `Hidden Gem Score`, `Country Availability`, `IMDb Score`, `Rotten Tomatoes Score`, `Boxoffice`, `View Rating`, and more.
- Raw data is stored in the `data/` folder (`netflix-rotten-tomatoes-metacritic-imdb.csv`).
- Cleaned dataset is also saved in `data/netflix_cleaned.csv` after preprocessing.


## Project Structure
data_analytics/
├── data/ # Raw and cleaned datasets
├── notebooks/Netflix_EDA.ipynb # Jupyter notebook for data cleaning, feature engineering, and exploratory data
├── dashboard/ -Yet to create
├── README.md # Project description