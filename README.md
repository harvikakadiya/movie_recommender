# movie_recommender
It builds a Movie Recommender System with Sentiment Analysis using a dataset of movie tweets. The notebook cleans tweets, applies NLTK’s sentiment analysis, and integrates this into recommendations.


## 📌Project Description
Recommender systems traditionally use collaborative filtering or content-based filtering. This project demonstrates a hybrid approach that combines social media sentiment analysis with recommendation techniques to provide more personalized movie suggestions.


## Steps covered in the notebook:

- Load and preprocess a dataset of movie-related tweets (movietweets.csv).

- Clean tweets (remove emojis, punctuation, stopwords).

- Perform sentiment analysis using NLTK VADER.

- Compute sentiment scores and integrate them into recommendation logic.

- Explore potential use of collaborative filtering and hybrid recommendation strategies.


## 🛠️ Technologies Used

- Python
- Pandas, NumPy for data manipulation
- NLTK for natural language processing and sentiment analysis
- Scikit-learn for ML utilities (decomposition, metrics, model selection)
- PyTorch for matrix factorization / deep learning approaches
- Matplotlib for data visualization


## 🚀 Getting Started

1. Clone the repository
git clone https://github.com/your-username/movie-recommender-sentiment.git
cd movie-recommender-sentiment

2. Install dependencies
It’s recommended to use a virtual environment. Install all requirements:
pip install -r requirements.txt

3. Prepare dataset
Place your dataset as movietweets.csv in the project root.
Ensure it has at least a tweets column.

4. Run the notebook
jupyter notebook "recommender.ipynb"


# 📊 Results

* Cleaned and preprocessed movie tweets.

* Performed sentiment analysis with VADER.

* Integrated sentiment into a recommender system pipeline.

* Demonstrated how social media signals can improve recommendations.


### 📜 License

This project is licensed under the MIT License.
