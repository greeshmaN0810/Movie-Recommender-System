# 🎬 Movie Recommendation System 📽️  

This project builds a **content-based movie recommendation system** using **Natural Language Processing (NLP) and Machine Learning**. The system analyzes movie metadata, extracts relevant features, and recommends similar movies based on textual similarity.

## 🚀 Features
- **Data Preprocessing**: Merging TMDb movie and credits datasets, extracting relevant features (genres, keywords, cast, crew, and overview).  
- **Text Cleaning & Processing**: Tokenization, stemming, and removing spaces to create meaningful tags.  
- **Vectorization**: Converting textual data into numerical form using **Bag of Words (BoW)** and **CountVectorizer**.  
- **Movie Similarity Calculation**: Utilizing **Cosine Similarity** to find and rank similar movies.  
- **Recommendation Function**: A function to suggest the top 5 most similar movies based on input.  
- **Model Persistence**: Storing processed data and similarity matrices using **Pickle** for fast retrieval.  

## 📂 Files  
- `tmdb_5000_movies.csv` & `tmdb_5000_credits.csv` - Raw datasets.  
- `movies_dict.pkl`, `similarity.pkl`, - Processed data and model files.  
- `app.py` (or main script file) - Python script implementing data processing and recommendation logic.  

## 🔧 Technologies Used  
- **Python** (Pandas, NumPy, ast, NLTK, Sklearn)  
- **Natural Language Processing (NLP)**  
- **Machine Learning** (CountVectorizer, Cosine Similarity)  
- **Pickle** for model storage  

## 🎯 How to Use  
1. Load the processed data from `movies_dict.pkl` and `similarity.pkl`.  
2. Call `recommend('Movie Title')` to get recommendations.  
3. Run the script in a Jupyter Notebook or Python environment.  

## 📌 Future Enhancements  
- Implement **TF-IDF Vectorization** for improved text processing.  
- Add **Collaborative Filtering** for hybrid recommendations.  
- Deploy as a **web application** using Flask or Streamlit.  
