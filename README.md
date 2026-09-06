# Movies Dataset Analysis

Pandas analysis of 4,803 movies — cleaned data, engineered features (release year, profit), and reformatted nested genre data. Found 2017 had the highest average rating (7.40) among years analyzed, and Avatar was the most profitable film with a profit of $2.55 billion.

## Dataset

4,803 rows covering budget, revenue, genres, release date, runtime, rating, tagline, and more.

## Tools Used

- Python (Pandas, NumPy)

## Analysis Breakdown

- Cleaned missing values (homepage, overview, release date, runtime, tagline) with appropriate fillers
- Converted data types: release date to datetime, status/language to category, runtime to numeric
- Extracted release year from release date
- Calculated average rating by year for selected years, and for 2009 specifically
- Engineered a `Profit` column (revenue − budget) and sorted to find top-performing films
- Reformatted nested JSON-style genre data into clean, readable genre lists

## Key Findings

- **2017** releases had the highest average rating (**7.40**) among the years analyzed (1980, 1999, 2004, 2017)
- Average rating for 2009 releases: **6.07**
- **Avatar** was the most profitable film, with a budget of $237M, revenue of $2.79B, and a **profit of $2.55 billion** — well ahead of the next highest (Titanic, $1.65B profit)

## Author

Sommya Loharuka

## Acknowledgement

This project was inspired by a publicly available YouTube tutorial on data cleaning and analysis with Pandas. All code was written, reviewed, and tested independently to deepen my understanding of data cleaning, feature engineering, and exploratory analysis.
