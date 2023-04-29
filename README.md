# movie-recommender-system
Introduction:
This is a movie recommendation system built using Python and CountVectorizer. The dataset used for this project contains information about movies such as budget, genres, homepage, keywords, original language, original title, overview, popularity, production companies, production countries, release date, revenue, runtime, spoken languages, status, tagline, title, vote average, and vote count.

Objective:
The objective of this project is to recommend movies to users based on their interests. The recommendation system uses CountVectorizer to convert the movie information into a matrix of token counts, which is then used to compute the similarity between movies.

Methodology:
The first step in building the recommendation system is to preprocess the movie data. This includes handling missing values, removing duplicates, and creating a new column that combines important movie features. Next, CountVectorizer is used to convert the movie data into a matrix of token counts. The token count matrix is then used to compute the cosine similarity between movies. Finally, the recommendation system recommends movies to users based on their interests.

Results:
The movie recommendation system recommends movies based on the cosine similarity between movies. For example, if a user is interested in a particular movie, the recommendation system will recommend other movies that are similar to the user's interests. The recommendation system can also be used to recommend movies based on a combination of interests.

Conclusion:
In conclusion, this project demonstrates how to build a movie recommendation system using Python and CountVectorizer. The system is able to recommend movies to users based on their interests. This project can be extended to other domains such as music, books, and products.
