# 🎬 AI-Powered Movie Recommendation System

An end-to-end Movie Recommendation System built using Machine Learning, FastAPI, Streamlit, and TMDB API. The application recommends similar movies using TF-IDF Vectorization and Cosine Similarity while providing real-time movie information, posters, genres, and details.

## 🚀 Features

- Movie search with keyword matching
- Content-based movie recommendations
- TF-IDF Vectorization and Cosine Similarity
- Real-time TMDB API integration
- Movie posters and detailed information
- Trending movies
- Popular movies
- Upcoming movies
- Genre-based recommendations
- Interactive Streamlit UI
- FastAPI backend with REST APIs
- Deployed on Render

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Machine Learning
- Scikit-Learn
- TF-IDF Vectorization
- Cosine Similarity

### Data Processing
- Pandas
- NumPy

### Backend
- FastAPI
- Uvicorn

### Frontend
- Streamlit

### API Integration
- TMDB API

### Deployment
- Render

### Version Control
- Git
- GitHub

---

## 📂 Project Structure

```bash
movie-recommendation-system/
│
├── app.py
├── main.py
├── requirements.txt
├── movies_metadata.csv
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
├── df.pkl
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/vishalkhairthal/AI-Powered-Movie-Recommendation-System.git
cd AI-Powered-Movie-Recommendation-System
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
TMDB_API_KEY=YOUR_TMDB_API_KEY
API_BASE_URL=YOUR_BACKEND_URL
```

---

## ▶️ Run FastAPI Backend

```bash
uvicorn main:app --reload
```

Backend URL:

```text
http://127.0.0.1:8000
```

API Documentation:

```text
http://127.0.0.1:8000/docs
```

---

## ▶️ Run Streamlit Frontend

```bash
streamlit run app.py
```

Frontend URL:

```text
http://localhost:8501
```

---

## 🧠 Machine Learning Approach

The recommendation engine uses:

1. Text preprocessing
2. TF-IDF Vectorization
3. Cosine Similarity
4. Content-Based Filtering

Movies with similar textual features are recommended based on similarity scores.

---

## 🌐 API Endpoints

### Health Check

```http
GET /health
```

### Home Feed

```http
GET /home
```

### Movie Details

```http
GET /movie/{tmdb_id}
```

### Recommendations

```http
GET /recommend/tfidf
```

### Genre Recommendations

```http
GET /recommend/genre
```

### Search Movies

```http
GET /search
```

---

## 🎯 Future Improvements

- Hybrid Recommendation System
- Collaborative Filtering
- User Authentication
- Watchlist Feature
- Movie Rating System
- Personalized Recommendations
- User Profiles

---

## 👨‍💻 Author

**Vishal Gupta**

B.Tech Computer Science Engineering

Data Science & Machine Learning Enthusiast

GitHub: https://github.com/vishalkhairthal

LinkedIn:https://www.linkedin.com/in/vishal-gupta-26b515218
---

## 📜 License

This project is developed for educational and portfolio purposes.