# Course Recommendation System using NLP and BERT

## 🔍 Problem Statement

With thousands of online courses available, learners often struggle to identify the most relevant courses that align with their professional background, skills, and career goals. Most platforms offer generic recommendations based on popularity or ratings, which lack personalization. This project aims to solve this real-world problem by building a **personalized course recommendation engine** that understands the **semantic profile** of a user and suggests courses tailored to their experience, education, and interests.

## 🚀 Project Overview

This project builds a **content-based recommendation system** using:
- Coursera course dataset (from Kaggle)
- LinkedIn profile dataset with education, projects, and experience fields
- Natural Language Processing (NLP)
- TFIDF and BERT-based embeddings
- Cosine similarity for course matching

## 📊 Key Features

- Preprocessing of semi-structured profile and course data
- TFIDF and Sentence-BERT embeddings for textual similarity
- Personalized top-N course recommendations
- Evaluation with qualitative examples and visualization
- Exploratory Data Analysis (EDA) of user profile trends

## 🧠 Techniques Used

- Text Cleaning (lowercasing, stopword removal, stemming)
- TFIDF Vectorization
- Sentence-BERT (SBERT) for semantic embeddings
- Cosine Similarity
- PCA (optional) for visualization or dimensionality reduction
- Matplotlib/Seaborn for EDA

## 📁 Folder Structure

```
├── data/                   # Datasets used (LinkedIn + Coursera)
├── notebook/               # Jupyter notebook with implementation
├── report/                 # Final project report (PDF)
├── README.md               
```

## 🔗 Datasets

- [Coursera Courses Dataset](https://www.kaggle.com/datasets/nileshrai/coursera-courses-dataset)
- [LinkedIn Profile Dataset](https://brightdata.com/products/datasets)

## 🧑‍🎓 Target Users

- Professionals exploring upskilling options
- Career switchers looking for tailored learning paths
- Universities/bootcamps recommending personalized courses

## 📌 Future Work

- Incorporate collaborative filtering
- Collect user feedback for real-time learning
- Add more context using experience duration, job roles, and goals
