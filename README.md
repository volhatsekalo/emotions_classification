# Emotion Classification Project

This project focuses on using a basic machine learning model to classify emotions based on text data.

## Project Overview

- **Goal:** Classify text inputs into different emotion categories (**sadness, joy, love, anger, fear, surprise**)
- **Dataset:** Publicly available emotion-labeled text dataset (loaded from Hugging Face Datasets).
- **Tech stack:** 
  - Python
  - Pandas
  - scikit-learn
  - nltk (for text preprocessing)

## Main Steps

1. **Data Loading:** Load and explore the emotion dataset.
2. **Text Preprocessing:** 
   - Tokenization
   - Stop-word removal
   - Lemmatization
3. **Feature Engineering:** 
   - TF-IDF vectorization
4. **Modeling:** 
   - Logistic Regression model for classification
5. **Evaluation:** 
   - Classification report
   - Confusion matrix visualization

## Results

Achieved good classification results on a small but representative dataset.  
Visualizations and evaluation metrics are provided inside the notebook.

## Future Improvements

- Test more advanced models (e.g., fine-tuned transformer models).
- Use a larger and more diverse dataset.
- Add hyperparameter tuning.

