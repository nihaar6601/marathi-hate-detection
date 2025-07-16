# Marathi Hate Speech Detection using NLP

This project focuses on detecting hate speech in Marathi tweets using Natural Language Processing (NLP) techniques.
The system classifies social media text into four categories: Hate, Offensive, Profane, and Neutral.

### Key Components:
#### 1. Data Preprocessing

Noise Removal:

 - Removed URLs, Twitter handles, punctuation, and special characters using regular expressions.

Stop Word Removal:

 - Eliminated common stop words (e.g., "a," "the," "is") that do not contribute to sentiment or context.

Tokenization & Lemmatization:

 - Split text into individual words and reduced them to their root forms for consistency.

POS Tagging & Unigram Model:

 - Tagged words with their parts of speech and used a unigram model to compute word probabilities.

#### 2. Feature Extraction
Count Vectorizer:

 - Converted text into numerical feature vectors.

Vocabulary Building:

 - Built unigram-based feature vectors mapped with POS tags for classification.

### 3. Classification Algorithms

Four machine learning models were used for text classification:

 - XGBoost	
 - Random Forest	
 - Logistic Regression	
 - Support Vector Machine

XGBoost resulted in the highest accuracy of 74.93%.

### Technologies Used:
 - Python (NLP preprocessing, ML models)

 - NLP Techniques: Tokenization, POS Tagging, Lemmatization, Count Vectorization

 - ML Libraries:

   - XGBoost

   - Scikit-learn (Random Forest, Logistic Regression, SVM)

### Dataset:
 - Marathi Tweets Dataset (curated for hate speech, offensive language, and profane content detection)

### Purpose:
 - This project demonstrates how machine learning and NLP can be applied to regional languages like Marathi to address real-world social issues, such as detecting hate and offensive content on social media.
