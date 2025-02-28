# Movie Recommendation System: Collaborative Filtering and Content-Based Approaches

## Project Overview
This project focuses on building a movie recommendation system using both collaborative filtering and content-based filtering techniques. The system aims to provide personalized movie recommendations based on user preferences and movie metadata.

## Dataset
Source: MovieLens Dataset
Data: User ratings and movie metadata (e.g., genre, cast, crew)
Preprocessing: Handling missing values, encoding categorical features, and scaling numerical data

## Methodology
1. Collaborative Filtering (CF)
- Utilized matrix factorization techniques (e.g., Singular Value Decomposition, SVD)
- Predicted user ratings based on similar user preferences
- Handled sparse data through dimensionality reduction
2. Content-Based Filtering (CBF)
- Analyzed movie metadata, including genres, cast, and crew
- Calculated similarity scores using techniques like cosine similarity
- Recommended movies with similar features to those previously liked by the user

## Future Improvements
- Integrate additional data sources, such as user reviews and social media sentiment
- Experiment with deep learning models (e.g., neural collaborative filtering)
- Implement a more dynamic and scalable recommendation engine using a web framework

## How to run the project/make edits
Clone the repository and install the required Python libraries listed in requirements.txt. Run the Jupyter Notebook movie_recommendation.ipynb to generate recommendations. Follow the provided instructions to input user data and explore recommendation results.

## Author
Will Markevitch and Andrew Hansen, wmarkevitch@ucsb.edu
