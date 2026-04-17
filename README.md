# Smart Recruit - Machine Learning Model

This repository contains the Machine Learning model used in the **Smart Recruit** system, a web-based platform designed to classify IT candidates into suitable job roles.

---

## 📌 Overview

The model is built using the **Naive Bayes algorithm** to classify candidates into three IT professions:

- Data Scientist  
- AI Engineer  
- Cybersecurity Engineer  

The classification is based on candidate profile data such as:
- Skills
- Certifications
- Education
- Experience (Years)
- Number of Projects

---

## 🧠 Machine Learning Approach

The model uses a combination of text processing and numerical features:

### 1. Text Features
- **Skills** → TF-IDF Vectorization  
- **Certifications** → TF-IDF Vectorization  

### 2. Categorical Feature
- **Education** → Encoded into numerical values  

### 3. Numerical Features
- Experience (Years)  
- Projects Count  

All features are combined and processed using the **Naive Bayes classifier**.

---

## 📊 Model Performance

Evaluation was performed using an **80:20 train-test split**.

| Metric       | Score |
|-------------|------|
| Accuracy    | 97.51% |
| Precision   | 0.98 |
| Recall      | 0.97 |
| F1-Score    | 0.97 |

The model shows strong performance with balanced results across all classes.

---

## 📂 Dataset

The dataset used in this project is sourced from the Kaggle platform and contains candidate profiles with the following attributes:

- Skills  
- Experience (Years)  
- Education  
- Certifications  
- Job Role (Label)  
- Projects Count  

After preprocessing and cleaning, the dataset was used for training and evaluation.

---

## 🚀 How to Run

1. Open the notebook
2. Run all cells to:
- Load dataset
- Preprocess data
- Train model
- Evaluate performance

---

## 🔗 Integration

This model is integrated into the **Smart Recruit web application (Flask)**, where:
- Users input candidate profile data
- The system predicts the most suitable job role
- Results are displayed in real-time on the website

---

## 👨‍💻 Author

**Yonathan Fransiscus Manalu**  
- **Email**: [yonatanfrans07@gmail.com](mailto:yonatanfrans07@gmail.com)
- **Linkedin**: [yonathanfrans](https://www.linkedin.com/in/yonathanfrans/)
- **Instagram**: [@yonathanfrans_](https://www.instagram.com/yonathanfrans_)

---

## 📌 Notes

- This project is part of a final thesis focused on implementing Machine Learning in recruitment systems.
- The model is designed for educational and research purposes.
