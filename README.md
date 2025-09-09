# 🎬 Movie Recommendation System

This project demonstrates how to build a **movie recommendation engine** using a synthetic dataset of 5,000 movies.  
Two approaches are implemented:

1. **Content-based Filtering** – recommends movies similar to a given one using metadata (genres, director, year, etc.)  
2. **Collaborative Filtering (SVD)** – recommends movies to users based on rating patterns (user–movie interactions)  

---

## 📂 Project Files
- `movie_recommendation.ipynb` → Jupyter Notebook with full code & explanations  
- `movies_dataset_5000.csv` → Synthetic dataset used for training (5,000 rows)  
- `requirements.txt` → Python dependencies (pandas, numpy, scikit-learn, etc.)  

---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/YOUR_USERNAME/movie-recommendation-system.git
cd movie-recommendation-system


python -m venv venv
# Activate venv
# macOS/Linux:
source venv/bin/activate
# Windows:
.\venv\Scripts\activate


pip install -r requirements.txt

jupyter notebook movie_recommendation.ipynb


📊 Methods Used
🔹 Content-based Filtering

Uses TF-IDF Vectorization on movie metadata (genres, director, year)

Calculates cosine similarity between movies

Given a movie, recommends the most similar ones

🔹 Collaborative Filtering (SVD)

Builds a user–movie rating matrix

Applies Truncated SVD (matrix factorization)

Finds hidden patterns in user preferences

Generates recommendations for a given user

🎯 Example Results

Content-based: Movies similar to Movie 25

Collaborative Filtering: Recommendations for User 50

🔮 Future Improvements

Add a hybrid recommender (combine content + collaborative)

Deploy app using Streamlit or Flask

Integrate real-world datasets like MovieLens

🛠️ Built With

Python

pandas, numpy

scikit-learn

Jupyter Notebook

👨‍💻 Author: Victor Ebere
🔗 LinkedIn- https://www.linkedin.com/in/victor-ebere-40a56014a
 | ✉️ vecharisma@gmail.com
