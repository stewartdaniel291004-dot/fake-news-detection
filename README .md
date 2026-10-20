
# Fake News Detection Using Machine Learning

## Overview
A Natural Language Processing project that classifies news articles
as Fake-labeled or Real-labeled using text features.

## Dataset
- Fake and Real News Dataset
- Fake.csv and True.csv
- Labels: 1 = Fake, 0 = Real
- Dataset annotations are used as the target labels.

## Methodology
1. Load and inspect the dataset.
2. Clean and combine news titles and article text.
3. Remove stopwords and apply lemmatization.
4. Split data into training and testing sets.
5. Convert text into TF-IDF features.
6. Train Logistic Regression and Linear SVM.
7. Evaluate accuracy, precision, recall and F1-score.
8. Visualize model comparison and confusion matrices.
9. Generate word clouds and test custom examples.

## Results

              Model  Accuracy  Precision  Recall  F1-score
Logistic Regression    0.9918     0.9939  0.9904    0.9921
         Linear SVM    0.9980     0.9982  0.9978    0.9980

Best model by F1-score: Linear SVM

## Tools
Python, Pandas, NLTK, Scikit-learn, Matplotlib,
WordCloud and Google Colab.

## Important Limitation
The model learns patterns in this dataset. Its predictions do not
independently verify whether a real-world news article is true or false.
