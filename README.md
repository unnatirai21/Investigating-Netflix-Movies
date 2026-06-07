### Investigating-Netflix-Movies
Conducted exploratory data analysis on Netflix movie data using Python, identifying runtime trends for 1990s films and analyzing genre-specific patterns through filtering, aggregation, and visualization techniques.

### Project Overview

Netflix offers a vast collection of movies and television content spanning multiple decades and genres. This project focuses on exploring movies released during the 1990s to better understand runtime patterns and genre-specific trends.

The analysis was conducted using Python and involved filtering, summarizing, and visualizing Netflix movie data.

### Dataset

The dataset contains information on Netflix titles, including:

* Show ID
* Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Duration
* Description
* Genre

### Objectives

* Analyze movies released during the 1990s.
* Identify the most common movie duration in the decade.
* Visualize the distribution of movie runtimes.
* Determine the number of short action movies released during the 1990s.

### Methodology

#### Data Preparation

* Imported the dataset using Pandas.
* Filtered records to include only movies.
* Selected movies released between 1990 and 1999.

#### Exploratory Data Analysis

* Calculated the most frequent movie duration using the mode.
* Created a histogram to visualize the distribution of movie durations.
* Filtered Action genre movies released during the 1990s.
* Identified movies with a duration of less than 90 minutes.

### Key Findings

* The most common movie duration among 1990s movies was **93 minutes**.
* Movie durations were concentrated around the 90–100 minute range.
* There were **7 action movies** released in the 1990s with runtimes below 90 minutes.

### Visualization

A histogram was used to examine the distribution of movie durations for 1990s movies and identify common runtime patterns.

### Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

### Conclusion

The analysis showed that 1990s movies on Netflix generally followed a standard runtime close to 93 minutes. Short-duration action movies were relatively uncommon, with only a small number of titles falling below the 90-minute threshold.
