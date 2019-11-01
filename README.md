# moviedata-analysis
Movies are more than just a story on a big screen, they are the attraction of the performers, charm of the genres and grandeur of the directors that lure audiences to the theatre or in today’s world, to the digital platforms. Gone are the days when viewers used to scour newspapers for information regarding films and in fact, they need not go through the hassle at all. We can utilize the power of analytics, visualization tools and immense penetration of internet to provide the stakeholders with relevant information wherever they want and whenever the want.
Keeping this in mind we set forth to produce an analysis report that could be used by:

Film production companies: To gain an insight on how budget and ratings affect the profitability of movies, which release month makes the most profit and in gaining insight into the changing taste of audience with respect to the genres.
Cineplex owners: In investing in the movies of most profitable directors or investing according to viewers taste.
The Audience: By providing them with a summary of top 10 movies with respect to each genre and the most popular directors.
To accomplish the aforementioned tasks we acquired a data file from Kaggle which provided us with information like overview of the movie, release date, revenue collected, runtime and language of the movie. We also downloaded additional data files from Kaggle which captured in detail the viewer ratings, the popularity and information regarding the cast and crew members of the movie. These files were blended together to fulfil the objectives.

A short description of our data
We have a dataset of movies from year 1894 to 2013 and contains approximately 47,000 records
The dataset has separate files for movie information, movie credits and movie ratings which we will be using
Variables having multiple values are in JSON Stringified format which we would be transforming
We will be working with 3 files in our movie dataset:

movies_metadata - contains details about the movie like title, overview, revenue, genres, popularity, country, production houses, etc
credits - contains cast, crew of all movies
rating - contains ratings of movies from more than 10,000 users
