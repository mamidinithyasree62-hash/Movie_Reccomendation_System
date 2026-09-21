# Movie_Reccomendation_System
README: Movie Data Analysis and Recommendation Project
This project provides a comprehensive analysis of a synthetic movie dataset, including exploratory data analysis, genre-based insights, and a simple recommendation system. The dataset consists of 400 movie records with details such as Movie_ID, Title, Genre, Release_Year, IMDb_Rating, Number_of_Votes, Language, and Duration_Minutes.

Project Features:
Synthetic Dataset Generation: Creates a dataset of 400 movie records with varied genres, release years (2000-2024), and IMDb ratings (5.0-9.5). Handles multiple genres per movie.
Top 10 Highest-Rated Movies: Identifies and displays the top 10 movies based on their IMDb ratings.
Genre Analysis:
Calculates the average IMDb rating for each genre.
Identifies the most popular genres by counting movie occurrences.
Determines genres with consistently high ratings by considering both average rating and movie count.
Temporal Trend Analysis: Visualizes how average IMDb ratings have changed over the years using a line chart.
Rating Distribution: Displays the overall distribution of movie ratings using a histogram.
Data Cleaning & Verification:
Handles missing values (specifically in IMDb_Rating).
Verifies and converts data types for consistency.
Expands multi-genre entries into a long-form DataFrame for easier analysis.
Movie Filtering: Allows users to filter movies based on a specified genre and a minimum IMDb rating threshold.
Movie Recommendation: Provides movie recommendations for a given genre, displaying movies with an IMDb rating of 8.0 or higher.
How to Use:
To run this project and explore the analyses, execute the code cells sequentially in a Jupyter Notebook or Google Colab environment.

Prerequisites:
Make sure you have the following Python libraries installed:

pandas
numpy
matplotlib
seaborn
You can install them using pip:

pip install pandas numpy matplotlib seaborn
Steps:
Run the Synthetic Data Generation Cell: This will create the movies_dataset.csv file and load it into a pandas DataFrame.
Execute Analysis Cells: Proceed to run the subsequent code cells to perform various data analyses and generate visualizations.
Interact with Filtering and Recommendation Cells: The cells for "Filter Movies by Genre and Rating Threshold" and "Recommend Movies by Genre and Minimum Rating" will prompt you for input in the console to get dynamic result
