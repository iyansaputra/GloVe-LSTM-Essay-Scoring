# 📚 Essay Scoring System using GloVe-LSTM and NLP Techniques

This project is part of my undergraduate thesis focusing on the automatic assessment of student essay answers using a combination of deep learning and natural language processing (NLP) methods.

## Objective
To develop a scoring model that can:
- Understand semantic meaning in student answers.
- Handle answers that don’t explicitly use keywords.
- Compare traditional scoring techniques (ROUGE, TF-IDF, Cosine Similarity) with a deep learning approach (GloVe-LSTM).

## Key Features
- Preprocessing student essays (tokenization, stopword removal, lowercasing, etc.)
- Feature extraction using:
  - **TF-IDF**
  - **Cosine Similarity**
  - **ROUGE Score**
- Deep learning model using:
  - **GloVe (Global Vectors for Word Representation)**
  - **LSTM (Long Short-Term Memory Neural Network)**

## Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Square Error)
- R² Score
- Pearson & Spearman Correlation

## Tech Stack
- Python (main language)
- TensorFlow, Scikit-Learn, NumPy, Pandas
- Google Colab for model training
- Flask for local web deployment

## Screenshots & Diagrams
- Model Architecture (`glove_lstm_architecture.png`)
- Dataset sample (`dataset_sample.png`)

## Note
All data used has been anonymized and simplified for educational use only.
