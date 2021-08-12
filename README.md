# Movies-ETL

## Overview

Amazing Prime Video is a platform for streaming movies and TV shows, I have been helping them to prepare the data for analysis using ETL (Extract, Transfer and Load). 

For this project, I conducted ETL process and add the data to a PostgreSQL database for three files: 

1.	[Wikipedia data](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/Resources/wikipedia-movies.json)
2.	[Kaggle metadata](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/Resources/movies_metadata.csv)
3.	MovieLens rating data

## Deliverables

There are four deliverables for this project:

1.	Deliverable 1: Write an ETL Function to Read Three Data Files

- [ETL_function_test.ipynb](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/ETL_function_test.ipynb)
-	Write functions to read and extract the files and data.

2.	Deliverable 2: Extract and Transform the Wikipedia Data

- [ETL_clean_wiki_movies.ipynb](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/ETL_clean_wiki_movies.ipynb)
-	Write functions to clean Wiki data. 
-	Clean columns and rows, convert data type and format.

3.	Deliverable 3: Extract and Transform the Kaggle data

- [ETL_clean_kaggle_data.ipynb](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/ETL_clean_kaggle_data.ipynb)
-	Write functions to clean Kaggle data.
-	Merge Wiki and Kaggle data. 
-	Clean merged data.
-	Extract and transfor MovieLens ratings data.

4.	Deliverable 4: Create the Movie Database

- [ETL_create_database.ipynb](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/ETL_create_database.ipynb)
- [movies_query.png](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/Resources/movies_query.png)
- [ratings_query.png](https://github.com/weihaolun/Movies-ETL/blob/51143ffa1b57385ec624361d401b20cde38367a4/Resources/ratings_query.png)
-	Load cleaned data to PostgreSQL database and run query to confirm.

