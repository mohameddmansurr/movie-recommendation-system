🎬 Movie Recommendation System
A collaborative filtering movie recommendation system built using the MovieLens 100K dataset.
This project implements user-based, item-based, and matrix factorization (SVD) methods to recommend movies to users.

📌 Features
User-based Collaborative Filtering – recommends based on similar user preferences.

Item-based Collaborative Filtering – recommends similar movies to those the user liked.

Matrix Factorization (SVD) – uncovers hidden patterns in ratings.

Evaluation with Precision@K – measures recommendation accuracy.

📂 Dataset
Source: MovieLens 100K Dataset

Contains 100,000 ratings from 943 users on 1,682 movies.

🛠 Tools & Libraries
Python

Pandas

NumPy

Scikit-learn

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/mohameddmansurr/movie-recommendation-system.git
cd movie-recommendation-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook "Movie Recommendation System.ipynb"
📊 Example Output
User ID	Recommended Movies
5	Toy Story, Star Wars, The Godfather
10	Pulp Fiction, Shawshank Redemption, Silence of the Lambs

