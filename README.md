# Real or Fake News Prediction System
This project is a comprehensive system for predicting whether a news article is Real or Fake using advanced machine learning techniques such as using logical regression model, decision tree classifier, random forest classifier and gradient boosting classifer. It emphasis upon declaring the reliability pf news using 3 models for confirmation.

![image](https://github.com/user-attachments/assets/8d90fd3f-8137-417a-bd9c-b6ae0ca60587)

## 📰 Overview
In today's digital age, the spread of fake news is a growing concern. This system tackles the problem by analyzing the text content of news articles and determining their authenticity. The project employs multiple machine learning models to ensure robust and accurate predictions.

## ✨ Features
-Text Preprocessing: Efficiently cleans and prepares textual data by removing noise (URLs, HTML tags, punctuation, etc.).
-Machine Learning Models:
-Logistic Regression
-Decision Tree Classifier
-Random Forest Classifier
-Gradient Boosting Classifier
Interactive Manual Testing: Test the system by inputting custom news articles and receiving real-time predictions.
-Performance Metrics: Evaluates the models using precision, recall, F1-score, and accuracy.
## 📂 Project Workflow
-**Dataset Preparation**:
-Combines real and fake news datasets.
**I sourced the dataset from Kaggle(fake-and-real-news-dataset
kaggle.com)**
-Assigns labels (1 for Real, 0 for Fake) and shuffles the data for balanced training.
-**Data Cleaning**:
-Removes irrelevant elements such as URLs, HTML tags, punctuation, and digits.
-**Vectorization**:
-Transforms text data into numerical format using TF-IDF Vectorizer.
-**Model Training**:
-Trains multiple machine learning models for comparison.
-**Prediction and Evaluation**:
-Predicts and evaluates results with detailed classification reports.
## 🔧 Technologies Used
Languages: Python
Libraries:
-pandas
-numpy
-scikit-learn
-re (Regular Expressions)
-TfidfVectorizer (from sklearn)
## 🚀 Usage
Prerequisites
Ensure the following Python libraries are installed:
   ```bash
pip install pandas numpy scikit-learn
   ```
### Steps to Run the Project
Clone the repository:
   ```bash
git clone https://github.com/your-repo-link.git
   ```
Navigate to the project directory:
   ```bash
cd fake-news-prediction
   ```
Run the script:
   ```bash
python fake_news_detection.py
   ```
Input a custom news article to test its authenticity:
   ```bash
news_article = input("Enter your news article: ")
print(manual_testing(news_article))
   ```
## 📊 Example Output
For a given input article:
   ```bash
"Government launches new healthcare scheme to benefit millions."
   ```
The output could be:
   ```bash
LR Prediction: Its Real
GBC Prediction: Its Real
RFC Prediction: Its Real
   ```
## 🔍 Results
The system evaluates performance based on:

**Accuracy**: Overall correctness of predictions.
**Precision**: Correctly identified positives as a proportion of total predicted positives.
**Recall**: Proportion of actual positives identified correctly.
**F1-Score**: Balance between precision and recall.
## 👩‍💻 Author
Prisha Prakash
📧 **Email**: [prishprakash9903@gmail.com](mailto:prishprakash9903@gmail.com)  
🌐 **LinkedIn**: [Prisha Prakash](https://www.linkedin.com/in/prisha-prakash-950816297)  


## 📜 License
This project is licensed under the MIT License.

Let me know if you'd like further customizations or additional sections!
