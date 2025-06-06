# Emotion Classification Model – Jayadhi AI/ML Entry Assignment

## 👤 Name
Md Harun Rashid

## 🏷️ Option Chosen
🅰️ Option 1: Emotion Classification Model

## 📁 Dataset
Used a text-emotion dataset with labeled emotions such as Happy, Sad, Angry, etc.  
Imported from a CSV file and cleaned before training.

## 🛠️ Approach
1. Preprocessed the text: lowercased, removed special characters.
2. Split the data into training and test sets.
3. Transformed text using TF-IDF vectorization with bigrams (`ngram_range=(1,2)`).
4. Trained a Logistic Regression model.
5. Evaluated using:
   - Classification Report
   - Accuracy Score
   - Confusion Matrix (visualized using Seaborn)
6. Deployed a Gradio interface to test real-time emotion prediction.

## 📊 Metrics
- Accuracy: (0.87)
- Confusion Matrix: Included in the output
- Classifier Report: Includes precision, recall, and F1-score

## 🧪 Libraries Used and Their Purpose

- pandas: Used for reading the CSV dataset and handling structured data (like DataFrames) efficiently.
- numpy: Supports numerical operations and array management, especially during preprocessing and model preparation.
- re: Regular expressions were used to clean the text by removing unwanted characters and symbols.
- scikit-learn: Core library for machine learning — used for:
  - Splitting the dataset
  - TF-IDF vectorization
  - Logistic Regression model
  - Model evaluation (accuracy, classification report, confusion matrix)
- matplotlib: Used for plotting graphs, especially to visualize the confusion matrix.
- seaborn: Built on matplotlib; made the confusion matrix visually intuitive with heatmaps.
- gradio: Built a user-friendly web UI for testing the model with real-time text input.

## ▶️ UI Demo
A Gradio interface is included for live text input and emotion prediction.

## 💡 Key Features
- Lightweight model, suitable for quick deployment
- Clean and readable code
- Simple UI for demonstration
- Uses publicly available data

---
