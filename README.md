# recommender_system
This repo is my application learning on Recommender Systems. I will explore different algorithms related to recommender systems, including Keras API for matrix factorisation.

The dataset is a reduced form of the Movie-Lens 20 Million data set. The data set has been processed to extract the top 10000 users and top 2000 movies in terms of ratings counts.

Additionally, the user id and movie ids have been preprocessed such that they exist in sequential numerical order. To be more specific, all user ids exist between 0 to 9999, and all movie ids exist between 0 to 1999. The dataset consist of the following columns:

- `userId`: User ID ranging from 0 to 9999.
- `movieId`: Movie ID ranging from 0 to 1999.
- `rating`: Rating that user gave to movie. Range from 0.5 to 5.0.