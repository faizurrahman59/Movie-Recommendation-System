# Project: Movie Recommender System Using Machine Learning

## Workflow
Recommendation systems are becoming increasingly important in today’s busy world. People are often short on time with numerous tasks to accomplish in a limited 24 hours. Recommendation systems help users make the right choices without expending too much cognitive effort.

The purpose of a recommendation system is to find content that is interesting to an individual. It uses factors like user profiles, search/browsing history, and what similar users are watching to create personalized recommendations. These systems are based on **Artificial Intelligence algorithms** that analyze data to generate relevant suggestions.

---

## Types of Recommendation Systems

### 1) Content-Based
- Uses item characteristics and attributes.
- Examples: Twitter, YouTube.
- Makes recommendations based on items similar to what the user has liked in the past.
- Limitation: Can be overly specialized, recommending only similar categories.

### 2) Collaborative Filtering
- Based on user-item interactions.
- Finds clusters of users with similar preferences.
- Example: Book or movie recommendations based on ratings.
- Limitation: Computationally expensive and new items may not get recommended.

### 3) Hybrid Systems
- Combines content-based and collaborative filtering approaches.
- Uses embeddings, word2vec, or other techniques.
- Avoids limitations of using only one approach.

---

## About This Project
This is a **Streamlit web application** that recommends movies based on user interests.  

- **Dataset:** TMDB 5000 movies  
- **Model:** Precomputed similarity matrix using **cosine similarity**.

### Cosine Similarity
- Measures similarity between vectors (here, movie features).  
- Value ranges from 0 to 1:  
  - `0` = completely different  
  - `1` = exactly similar  
- More details: [Cosine Similarity Guide](https://www.learndatasci.com/glossary/cosine-similarity/)

---

# How to run?
### STEPS:

Clone the repository

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movie python=3.7.10 -y
```

```bash
conda activate movie
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
```

Now run,
```bash
streamlit run app.py
```

