
# Movie Ratings and Genre Analysis System Using Oracle PL/SQL

## Student Information
- **Student Name:** Umwari Pamella
- **Student ID:** 20251SEN151
- **Course:** INSY 8311 – Database Development with PL/SQL
- **Instructor:** Eric Maniraguha

## 1. Project Overview
This project aims to develop an Oracle-based system for managing and analyzing movie ratings and genres. It will organize movie information and user ratings, identify highly rated movies, analyze popular genres, and present insights through an interactive dashboard.

## 2. Problem Statement
Movie information and ratings can be difficult to organize and compare when stored in different sources. This project proposes a centralized database to manage movie details, genres, and user ratings, making movie analysis easier.

## 3. Project Objectives

### Main Objective
To develop an Oracle PL/SQL-based system for managing and analyzing movie ratings and genres.

### Specific Objectives
- To store and manage movie information.
- To organize movies according to their genres.
- To record and analyze movie ratings.
- To identify highly rated movies and popular genres.

## 4. Data Source
The project will use the **MovieLens 100K Dataset** provided by GroupLens Research, University of Minnesota.

- Dataset: https://grouplens.org/datasets/movielens/100k/
- Contains 100,000 ratings from 943 users on 1,682 movies.
- Includes movie information and genre indicators.
- Ratings range from 1 to 5.

## 5. Planned Database Tables
The database will contain the following main tables:

- **MOVIES:** Stores movie information.
- **GENRES:** Stores movie genre information.
- **MOVIE_GENRE:** Connects movies with their genres.
- **USER_ACCOUNT:** Stores user account information.
- **RATING:** Stores user ratings for movies.

## 6. Planned PL/SQL Features
- **Procedures:** For managing movie records.
- **Functions:** For calculating average movie ratings.
- **Cursors:** For retrieving movie rating reports.
- **Triggers:** For validating movie ratings.
- **Packages:** For organizing database operations.
- **Exception Handling:** For handling invalid data and database errors.

## 7. Planned Innovation
The project will use **Oracle Application Express (APEX)** to develop an interactive user interface connected to the Oracle database. Users will be able to interact with movie information and view rating and genre analysis through dashboards.

## 8. Expected Results
A functional Oracle database system that organizes movie information and ratings, generates useful reports, identifies highly rated movies and popular genres, and displays movie analysis through an interactive dashboard.

## 9. References

1. Makita Makita, E. A., & Lenskiy, A. (2016). A multinomial probabilistic model for movie genre predictions. *International Journal of Machine Learning and Computing, 6*(2), 97–100. https://doi.org/10.18178/ijmlc.2016.6.2.580

2. Subramaniyaswamy, V., Logesh, R., Chandrashekhar, M., Challa, A., & Vijayakumar, V. (2017). A personalised movie recommendation system based on collaborative filtering. *International Journal of High Performance Computing and Networking, 10*(1–2), 54–63. https://doi.org/10.1504/IJHPCN.2017.083199

3. European Commission, Directorate-General for Communications Networks, Content and Technology. (2025). *Study on audiences, consumer behaviour and preferences relating to the consumption of media content*. https://doi.org/10.2759/5502681

4. IMDb. (2026). *Ratings FAQ*. https://help.imdb.com/article/imdb/track-movies-tv/ratings-faq/G67Y87TFYYP6TWAV

5. GroupLens Research. (1998). *MovieLens 100K dataset* [Data set]. University of Minnesota. https://grouplens.org/datasets/movielens/100k/

6. Oracle. (2019). *Oracle Database PL/SQL Language Reference*. https://docs.oracle.com/en/database/oracle/oracle-database/19/lnpls/
