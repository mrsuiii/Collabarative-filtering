# Movie Recommendation System

This project aims to develop a collaborative filtering-based movie recommendation system. It uses a matrix factorization model to learn movie and user parameters with stochastic gradient descent (SGD).


## Why Collabarative?
Consider case where you liked a movie, you tell your friends that the movie you liked and suggest them that movie. So the idea of collaborative filtering is to give recommendation based on what similar user like.
Furthermore, Collaborative filtering not only can be used as candidate generator for a Recommendation system, but also can be used for make recommendations itself.

## Features

- **Collaborative Filtering:** Provides personalized movie recommendations based on user ratings.
- **Matrix Factorization:** Learns latent features for both movies and users.
- **Efficient Training:** Uses SGD for fast and scalable optimization.

## Usage

This recommendation system personalizes the user experience by suggesting movies that match their preferences. It is ideal for streaming platforms, movie review websites, and any application that seeks to enhance user engagement through personalized content.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/mrsuiii/Collabarative-filtering.git
2. **Install Requirements**
   ```bash
   pip install numpy pandas torch
3. **Run the Notebook**

## Future Improvement
We may consider more advanced recommendation system, with additional method such as adding multiple step like candidate retrieval, scoring, reranking.
