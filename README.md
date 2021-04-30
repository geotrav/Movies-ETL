# Movies-ETL

### Project purpose
Write code that will allow a series of functions to load, clean, and merge movie data from three sources and load into a PostGres SQL database tables.  This process will extract and transform a webscraped data from a Wikipedia movies JSOn file, a Kaggle movie csv and ratings data csv from Movielens database.

### Results

1. Define a function that loadd the three files
2. Clean and merge the files through a series of steps 
	- eliminating null values
	- eliminate columns with more than 90% nulls
	- extract data into Pandas DataFrames
	- clean movie data
	- examining similar data from the two tables and selecting the data to keep and data to replace
	- eliminate redundant columns
	-use REGEX to extract and format the appropriate budget, release date, running time, and box office data
	- transform and merge in Kaggle data
3. Create cleaned merged movies dataframe
4. Export to PostgreSQL movies and ratings dataframes


### Summary 

Four jupyter notebook files are located in the repository and the resources folder contains the input data JSOn and CSV files as well as the following two images of the line counts from the SQL tables.

Image 1
![movies_query](/Resources/movies_query.png)

Image 2
![ratings_query](/Resources/ratings_query.png)




