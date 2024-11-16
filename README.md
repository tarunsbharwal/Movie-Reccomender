# Movie Recommender System

This is a Movie Recommender System project that uses a Content-Based approach to suggest movies to users based on their preferences. The project utilizes the IMDB dataset and Kaggle as data sources, and it's built as a Streamlit web application.
.
<img width="1440" alt="Screenshot 2023-08-28 at 5 21 24 PM" src="https://github.com/newsid2024/Microsoft_project_MovieRecommender/assets/108874631/d65f16d3-e2d5-45cd-b731-258e178232b6">
<img width="1440" alt="Screenshot 2023-08-28 at 5 21 42 PM" src="https://github.com/newsid2024/Microsoft_project_MovieRecommender/assets/108874631/b8dffe5d-c38f-410c-b9ba-1cc43763e392">
<img width="1440" alt="Screenshot 2023-08-28 at 5 21 57 PM" src="https://github.com/newsid2024/Microsoft_project_MovieRecommender/assets/108874631/f763c868-a857-408a-8921-1781654ca58e">
<img width="1440" alt="Screenshot 2023-08-28 at 5 22 05 PM" src="https://github.com/newsid2024/Microsoft_project_MovieRecommender/assets/108874631/cb9d1054-7671-4f95-a6f7-a37ad3e47c90">


## Features

- Content-Based Recommender System
- exploratory data analysis and cleaning of the dataset has been done.
- Similarity score calculation using cosine distance technique.(It is a numerical value that falls within the range of zero to one, serving as a gauge to determine the level of similarity between two items based on a scale. This score is derived by assessing the likeness between the textual attributes of the two items in question. In essence, the similarity score gauges how closely related two items are by evaluating their textual attributes. This evaluation can be executed using techniques like cosine similarity).
  
- Uses IMBD Api to search the info of movie.

## Installation

1. Clone this repository:

   ```
   git clone https://github.com/yourusername/movie-recommender.git
   ```

2. Change to the project directory:

   ```
   cd movie-recommender
   ```

3. Install required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

1.Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
2. Run the Streamlit app:

   ```
   streamlit run app.py
   ```

3. Open your web browser and go to `http://localhost:8501` to access the Movie Recommender System.


## Data Sources

- Kaggle dataset:[[link to the dataset]](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)



---
