# Movie-Recommender-System
A Content-Based Movie Recommendation System in Python that suggests 5 similar movies for any given title using the TMDB 5000 Movie Dataset. Features include TF-IDF vectorization, cosine similarity, and data preprocessing with null value removal, delivering accurate, feature-based movie suggestions directly from plot, genre, and keyword analysis.

📌 Dataset
Source: TMDB 5000 Movie Dataset from Kaggle
Data Cleaning: Removed null values and unnecessary columns for optimized processing

🔍 Methodology
Data Preprocessing – Cleaned and formatted dataset for analysis
Text Vectorization – Applied TF-IDF Vectorization to represent movie descriptions
Similarity Measure – Calculated Cosine Similarity to find closest matches
Content-Based Filtering – Recommends movies based on similarity in overviews, genres, and keywords

🛠 Tech Stack
Python (Pandas, NumPy, Scikit-learn)
Jupyter Notebook

TMDB Dataset
TF-IDF Vectorizer & Cosine Similarity

🚀 Features
Takes any movie title as input
Returns top 5 similar movies
Efficient and scalable for large datasets
Handles missing data gracefully
