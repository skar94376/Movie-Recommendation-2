CONTENT - BASED MOVIE RECOMMENDATION. Dataset from Kaggle. movies are from 1995 to 2016. The algorithm finds the most similar movies to a given movie. It takes into account the following attributes: 
Title similarity | Genres similarity | Average user ratings | Number of user ratings | User given tags similarity | Movie year |
Each of the above attribute is given a weight which can be tuned to get the best possible result.   For better performance of "tag" and "title" words analysis, the most frequent English words from the tags and movie titles using NLP's stopwords.  Finally I created the recommendation algorithm and made some recommendation at the end. 

Enter the movieId and the model will return back the movies similar to it.
