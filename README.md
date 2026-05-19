# 🎓 Data Science Capstone Projects — YHills Internship

**Intern Name:** Katta Srilaxmi Reddy
**Company:** YHills — Learning Beyond Expectations
**Internship Track:** Data Science
**GitHub:** github.com/kattasrilaxmireddy/Data-Science-Capstone-YHills

-----

## 📋 Projects Summary

|#|Project                    |Type                |Dataset                       |Status     |
|-|---------------------------|--------------------|------------------------------|-----------|
|1|Customer Churn Prediction  |Classification      |Telco Customer Churn (Kaggle) |✅ Completed|
|2|House Price Prediction     |Regression          |House Prices Advanced (Kaggle)|✅ Completed|
|3|Movie Recommendation System|AI + Personalization|MovieLens 100K                |✅ Completed|
|4|Credit Card Fraud Detection|Anomaly Detection   |Credit Card Fraud (Kaggle)    |✅ Completed|
|5|Sentiment Analysis         |NLP                 |IMDB Movie Reviews            |✅ Completed|

-----

## 📌 PROJECT 1: Customer Churn Prediction

### What This Project Does

Predicts whether a customer will leave a telecom company using machine learning.

### Dataset

- Telco Customer Churn — Kaggle
- 7,043 customers · 21 features

### Models Used

- Logistic Regression
- Random Forest ✅ Best Model
- XGBoost

### Results

- ROC-AUC Score: ~0.85
- Month-to-month customers churn at 43% rate
- Top factors: Contract type, Tenure, Monthly Charges

### How to Run

```
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
Run: Customer_Churn_Prediction.ipynb
```

-----

## 📌 PROJECT 2: House Price Prediction

### What This Project Does

Predicts sale price of houses based on size, location, quality and age.

### Dataset

- House Prices Advanced Regression — Kaggle
- 1,460 houses · 81 features

### Models Used

- Linear Regression
- Ridge Regression
- XGBoost ✅ Best Model

### Results

- Average Prediction Error: ~$15,975
- R² Score: ~0.92
- Top feature: Overall Quality Rating

### How to Run

```
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
Run: House_Price_Prediction.ipynb
```

-----

## 📌 PROJECT 3: Movie Recommendation System

### What This Project Does

Recommends movies to users based on genre similarity — like Netflix.

### Dataset

- MovieLens 100K — GroupLens
- 100,000 ratings · 943 users · 1,682 movies

### Approach Used

- Content-Based Filtering (TF-IDF + Cosine Similarity) ✅

### Results

- Successfully recommends similar movies by genre
- Top rated: Schindler’s List, Star Wars, Shawshank Redemption

### How to Run

```
pip install pandas numpy matplotlib seaborn scikit-learn
Run: Movie_Recommendation_System.ipynb
```

-----

## 📌 PROJECT 4: Credit Card Fraud Detection

### What This Project Does

Detects fraudulent transactions from 284,807 credit card transactions.

### Dataset

- Credit Card Fraud Detection — Kaggle
- 284,807 transactions · only 492 frauds (0.17%)

### Models Used

- Random Forest Classifier ✅

### Results

- 56,860 legitimate transactions correctly identified
- 80 fraud cases correctly caught
- Only 18 fraud cases missed

### How to Run

```
pip install pandas numpy matplotlib seaborn scikit-learn
Run: Credit_Card_Fraud_Detection.ipynb
```

-----

## 📌 PROJECT 5: Sentiment Analysis (NLP)

### What This Project Does

Classifies IMDB movie reviews as Positive or Negative using NLP.

### Dataset

- IMDB Movie Reviews — HuggingFace
- 25,000 reviews · 12,500 positive · 12,500 negative

### Models Used

- Logistic Regression + TF-IDF ✅

### Results

- Model Accuracy: ~89%
- “This movie was absolutely amazing!” → POSITIVE 😊 (74.1%)
- “Terrible film, waste of time!” → NEGATIVE 😞 (98.4%)

### How to Run

```
pip install pandas numpy matplotlib seaborn scikit-learn nltk datasets
Run: Sentiment_Analysis.ipynb
```

-----

## 🛠️ Tools Used

|Category        |Tools                      |
|----------------|---------------------------|
|Language        |Python 3                   |
|Environment     |Jupyter Notebook · Anaconda|
|Data Processing |pandas · numpy             |
|Visualization   |matplotlib · seaborn       |
|Machine Learning|scikit-learn · XGBoost     |
|NLP             |NLTK · HuggingFace · TF-IDF|
|Platform        |Kaggle · GitHub            |

-----

## 🏆 Key Learnings

1. Data cleaning matters more than model choice
1. Always choose the right evaluation metric
1. Start simple before going complex
1. Imbalanced datasets need special handling
1. Visualization helps communicate results

-----

## 📬 Contact

- **Name:** Katta Srilaxmi Reddy
- **Email:** kattasrilaxmireddy@gmail.com
- **GitHub:** github.com/kattasrilaxmireddy
- **Internship:** YHills — Learning Beyond Expectations
- **Website:** yhills.com

-----

*Completed as part of the YHills Data Science Internship Program* 🎓
