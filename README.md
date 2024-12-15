# Fake_News

This project implements a Fake News Detector using a machine-learning approach. It uses the Passive passive-aggressive classifier and TF-IDF Vectorizer to classify news articles as either fake or real. The project uses Python libraries such as numpy, pandas, matplotlib, seaborn, and sci-kit for data preprocessing, visualization, and model building.

# Steps

- **Data Preprocessing:** This process loads and preprocesses news articles from a dataset and visualizes the distribution of real vs. fake articles with Seaborn.
- **TF-IDF Vectorization:** Converts text data into numerical vectors using the TfidfVectorizer. Removes stop words and limits the maximum document frequency for better model performance.
- **Classification:** Implements the Passive Aggressive Classifier for classification. Splits the dataset into training and testing subsets.
- **Model Evaluation:** Measures accuracy of predictions using accuracy_score. Displays confusion matrix to analyze classification errors.

# Results

The classifier achieves an accuracy of approximately 92.3%.

# Dataset
The dataset used in this project must be a CSV file containing: <br>

**text:** The content of the news articles.<br>
**label:** A binary label (FAKE or REAL) indicating the article's authenticity.<br>

# License
Distributed under the MIT License. See LICENSE for more information.

# Acknowledgments
This project was inspired by Salah Sammar: Advanced Python Project - Detecting Fake News on Kaggle. 


