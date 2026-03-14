# Mental Disorder Analysis using NLP

## Overview
This project uses **Natural Language Processing (NLP)** and **machine learning techniques** to analyze textual data and classify mental health conditions such as **depression, anxiety, and bipolar disorder**. By analyzing language patterns in conversations and posts, the project demonstrates how machine learning can help identify indicators of mental health disorders.

---

## Objective
- Analyze mental health related text data  
- Apply NLP preprocessing and feature extraction  
- Train machine learning models to classify mental disorders  
- Compare model performance across different algorithms  

---

## Datasets
The project uses multiple datasets containing textual data related to mental health discussions, including datasets focused on:

- Depression  
- Anxiety  
- Bipolar disorder  
- Therapist–patient conversations  

These datasets were combined to build and evaluate classification models.

---

## Methodology

### Text Preprocessing
- Lowercase conversion  
- Stopword removal  
- Tokenization  
- Lemmatization  
- Removal of punctuation and noise  

### Feature Engineering
- TF-IDF vectorization  
- Sentiment analysis  
- Cosine similarity  
- SMOTE for class imbalance  

### Machine Learning Models
- Multinomial Naive Bayes  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- XGBoost  

---

## Results

The models demonstrated strong classification performance:

| Model | Depression | Anxiety + Bipolar |
|------|------|------|
| SVM | 92.94% | **94.75%** |
| Decision Tree | 90.42% | 84.48% |
| Random Forest | 93.52% | 94.21% |
| XGBoost | **94.97%** | 93.22% |
| Naive Bayes | 90.64% | 94.34% |

**XGBoost performed best on the depression dataset, while SVM performed best on anxiety and bipolar classification.**

---

## Key Insights
- Language patterns can reveal indicators of mental health conditions.  
- Sentiment and emotional expressions play an important role in classification.  
- Ensemble models such as Random Forest and XGBoost performed strongly for this task.  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Business / Real-World Impact
This project demonstrates how NLP and machine learning can convert unstructured mental health text into meaningful insights. Such models could support early screening, assist mental health professionals by highlighting concerning patterns in conversations, and improve automated mental health tools such as chatbots and digital health platforms.

---

## Disclaimer
This project is intended for **research and educational purposes only** and should not be used for medical diagnosis.
