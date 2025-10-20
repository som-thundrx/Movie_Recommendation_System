# Movie_Recommendation_System

---

## 🚀 Features

* Recommends movies based on similarity of content.
* Uses **TF-IDF Vectorizer** for text representation.
* Calculates similarity using **Cosine Similarity**.
* Finds closest movie titles using **difflib**.

---

## 🧠 Tech Stack

* Python
* NumPy
* Pandas
* scikit-learn
* difflib

---

## ⚙️ How It Works

1. The dataset (movies.csv) contains movie titles, genres, and metadata.
2. Text data is converted into numerical vectors using **TF-IDF Vectorizer**.
3. **Cosine Similarity** computes similarity scores between movies.
4. When a user enters a movie name, **difflib** finds the closest match.
5. The top similar movies are displayed as recommendations.

---


## 📊 Sample Output

```
Enter your favorite movie: Avatar
Movies suggested for you:

1. Guardians of the Galaxy  
2. Star Trek  
3. The Fifth Element  
4. Interstellar  
5. The Matrix  
...
```

