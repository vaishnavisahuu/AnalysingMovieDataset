2.4
Python Fundamentals: Analyzing Movie Data Set
104
Task
Different functions that you would require to define for this project has been mentioned in the code block. All the parameters and the task a function would do, has been mentioned there.

The data file has already been loaded for you and stored as a list in movies

The first row is the header. Extract and store it in movies_header
Subset the movies dataset such that the header is removed from the list and store it back in movies
Delete the wrong data. Explore row #4553. You will see that as apart from the id, description, status and title, no other information is available.
Hence drop this row.
Using explore_data() with appropriate parameters, view the details of the first 5 movies.
Our dataset might have more than one entry for a movie. Call duplicate_and_unique_movies() with index of the name to check the same.
We saw that there are 3 movies for which there are multiple entries.
Create a dictionary, reviews_max that will have the name of the movie as key, and the maximum number of reviews as values.
Create a list movies_clean, which will filter out duplicate movies and contain the rows with the maximum number of reviews for duplicate movies, as stored in 'review_max'.
Calling movies_lang(), extract all the English movies and store it in movies_en.
Call the rate_bucket function to see the movies with a rating higher than 8 and store the resulting list in high_rated_movies.
Skills Covered:
