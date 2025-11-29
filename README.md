# FUTURE_DS_03
# 🗣️ College Event Feedback — Sentiment Analysis (NLP)
### Data Science & Analytics Internship – Future Interns  
### Task 3 Submission

---

## 📌 Project Overview
This project focuses on analyzing student feedback collected from various college events such as workshops, hackathons, seminars, cultural festivals, and placement sessions.  
The goal is to clean the feedback, perform sentiment analysis, and extract insights that can help organizers improve event quality.

---

## 🗂 Dataset Details
The dataset used contains:
- Student_Name  
- Department  
- Event_Name  
- Rating  
- Feedback  
- Date  
- Feedback_clean  
- polarity_textblob  
- vader_compound  
- sentiment_textblob  
- sentiment_vader  
- sentiment (Final label)

Processed file: **`feedback_processed_task3.csv`**

---

## 🧰 Tools & Libraries
- **Python (Google Colab)**
- **Pandas**
- **NLTK**
- **TextBlob**
- **VADER Sentiment Analyzer**
- **Matplotlib**
- **Wordcloud**

---

## 🧮 Methodology

### ✔ 1. Data Cleaning  
- Lowercasing  
- Removing URLs  
- Removing punctuation  
- Stopword removal  
- Creating `Feedback_clean` text

### ✔ 2. Sentiment Analysis  
- TextBlob polarity score (range: −1 to +1)  
- VADER compound score  
- Final sentiment label assignment:
  - Positive
  - Neutral
  - Negative

### ✔ 3. Visualization  
- Sentiment distribution bar chart  
- Event-wise sentiment stacked bar chart  
- Wordclouds of positive & negative feedback

---

## 📊 Key Outputs
- Processed CSV → `feedback_processed_task3.csv`  
- Jupyter Notebook → `Task3_Sentiment_Analysis.ipynb`

---


---

## 👩‍💻 Author
**Shruti Shreya**  
Data Science & Analytics Intern  
Future Interns

---

## 🙏 Acknowledgment
This project is completed as part of the **Future Interns — Data Science & Analytics Internship (Task 3)**.

