 # 🍿 CineMatch AI – Movie Recommendation System

CineMatch AI is an AI-powered movie recommendation web application built using **Streamlit** and **Python**, and deployed on **Render**. It uses a **graph-based approach with Uniform Cost Search (UCS)** to generate accurate movie recommendations based on genres and keywords.

---

## 🚀 Features

- 🎯 Graph-Based Recommendation Engine  
- 🧠 Uniform Cost Search (UCS) Algorithm  
- 🎬 TMDB Poster Integration  
- 💡 Interactive UI using Streamlit  
- ☁️ Deployed on Render for stable hosting  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- Pandas  
- NumPy  
- Scikit-learn  
- Requests  
- Render (Deployment)  

---

## 📁 Project Structure

```
AI-Movie-Recommendation/
│
├── app.py
├── requirements.txt
├── render.yaml
├── data/
│   ├── movies.csv
│   ├── credits.csv
│   └── ratings.csv
```

---

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

Then open:
```
http://localhost:8501
```

---

## 🌐 Live Demo

👉 https://ai-movie-recommendation-61xj.onrender.com/

*(Note: App may take 20–60 seconds to load due to free hosting sleep mode.)*

---

## 🧠 How It Works

1. Movie data is loaded from dataset files.  
2. A graph is created where each movie is a node.  
3. Edges are formed using shared genres and keywords.  
4. Uniform Cost Search (UCS) finds the most relevant recommendations.  

---

## ⚠️ Notes

- Free hosting may cause slow initial loading.  
- Large datasets can impact performance.  

---

## 👨‍💻 Authors

Shruti Mandlik
Vinshi Manwatkar
