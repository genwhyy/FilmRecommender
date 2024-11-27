# Movie Recommendation System

## Overview
This is a fully implemented movie recommendation system designed to suggest films with unique characters, plots, and themes, moving beyond the typical franchise or sequel-based recommendations. The project leverages advanced Machine Learning (ML) and Deep Learning (DL) techniques to provide personalized and diverse movie suggestions.

## Features
- Recommends movies with similar themes, character archetypes, and narrative structures.
- Focuses on unique and diverse content instead of franchise-based suggestions.
- Uses advanced textual data analysis to capture the essence of movie storylines.

## How It Works
1. **Data Preprocessing**: Cleans and prepares movie descriptions and keywords for analysis.
2. **Vectorization**: Uses TF-IDF to represent movie overviews and keywords in a numerical format.
3. **Embedding Extraction**: Employs the BERT model to generate contextual embeddings from the textual data.
4. **Similarity Scoring**: Computes cosine similarity between movies to find the most relevant recommendations.

## Tech Stack
- **Python**: For coding the entire pipeline.
- **Scikit-learn**: For TF-IDF vectorization and cosine similarity computation.
- **Transformers Library**: To utilize the BERT model for embedding extraction.
- **Pandas**: For data handling and manipulation.
- **PyTorch**: To implement deep learning techniques.
- **Jupyter Notebook**: For running and visualizing the project.

## How to Use
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/FilmRecommender.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-recommendation-system
   ```
3. Open the Jupyter Notebook file `movie_recommendation_system.ipynb`:
   ```bash
   jupyter notebook movie_recommendation_system.ipynb
   ```
4. Run all cells in the notebook.
5. Enter the name of a movie in the input field, and the system will suggest similar movies.

## Example
Input:
```
"Inception"
```

Output:
```
1. Interstellar
2. The Matrix
3. Shutter Island
4. The Prestige
5. Tenet
```

## Why This Project?
I created this project to explore the potential of advanced text-based analysis in recommendation systems. Unlike traditional approaches, this system uses the semantic richness of movie descriptions to provide recommendations that are both unique and relevant.

## Acknowledgments
The dataset was sourced from publicly available APIs like TMDB and IMDb. The project uses state-of-the-art tools and models such as BERT to ensure high-quality recommendations.
