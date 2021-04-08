## Movies-ETL
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. The purpose of the analysis is to clean and merge data using ETL process. Britta needs help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Module Code needs to be refactored by creating a function that takes three files:

- ### Wikipedia
- ### Kaggle Metadata
- ### MovieLens Rating Data 

All the three above files will perform Extract, Transfer and load process (ETL) by adding the data to a PostgreSQL Database. 

## Results:
### Deliverable 1: ETL Function to Read Three Data Files
![wiki-movies-df-DataFrame_1](./Resources/wiki-movies-df-DataFrame_1.png)
![kaggle-metadata-DataFrame_1](./Resources/kaggle-metadata-DataFrame_1.png)
![ratings-DataFrame_1](./Resources/ratings-DataFrame_1.png)

### Deliverable 2: Extract and Transform the Wikipedia Data

![wiki-movies-df-DataFrame_2](./Resources/wiki-movies-df-DataFrame_2.png)
![wiki-movies-df-columns_2](./Resources/wiki-movies-df-columns_2.png)


### Deliverable 3: Extract and Transform the Kaggle data
![movies-df-DataFrame_3](./Resources/movies-df-DataFrame_3.png)
![movies-with-ratings-df-DataFrame_3](./Resources/movies-with-ratings-df-DataFrame_3.png)


### Deliverable 4: Create the Movie Database
![ETL_ratings_4](./Resources/ETL_ratings_4.png)


## Summary:
After completing the extract, transform, and load process, I had a database with two tables: one for movies and one for ratings.
- The movie data from Wikipedia and Kaggle from their respective files, transform the datasets by cleaning them and merging them together, then load the cleaned dataset into a SQL database.The "movies" table contains 6,052 rows based on the kaggle and wikipedia data. 


![movies_query](./Resources/movies_query.png)


- The "ratings" table includes 26,024,289 rows of data.
![ratings_query](./Resources/ratings_query.png)
