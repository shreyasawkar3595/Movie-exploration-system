# Movie-exploration-system
The system acts a ratings generator using live twitter feed to evaluate the rating of a movie as well as a recommendation engine to recommend movies to the users based a dataset.

Ratings generator:

The front end is developed as an android app.The backend runs on a remote desktop where we install R. The steps to install R are as follows: https://cran.r-project.org/bin/windows/base/ and run the script.R.

To switch on the server we run the Server.java and ImageServe.java files which will now be ready to take in any movie name and pull out a rating along with an interactive movie cloud.The files needed for the back end are checked in the scripts folder.


Recommendation engine:

To train our recommendation engine we have used the data set provided by Movie Lens : https://movielens.org. To fetch recommendations we make use of clustering based on the genre of the movie.
