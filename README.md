# movie_spring
# Movie Review Application

This Spring Boot application allows you to manage movies and reviews in a MongoDB database. It provides a RESTful API to perform various operations related to movies and reviews. 

### 1. Movie Listing

- Retrieve a list of all movies in the database.
- Endpoint: `GET /api/v1/movies`

### 2. Movie Details

- Get detailed information about a specific movie by providing its IMDb ID.
- Endpoint: `GET /api/v1/movies/{imdbId}`

### 3. Review Creation

- Create and submit reviews for movies.
- Endpoint: `POST /api/v1/reviews`
- Requires the movie IMDb ID and review body in the request payload.




