# 🎬 IMDB Reviews Sentiment Analysis using LSTM

## 📌 Project Overview

This project performs **sentiment analysis on IMDB movie reviews** using a **Long Short-Term Memory (LSTM)** neural network.

The goal is to classify movie reviews as **Positive** or **Negative** based on their textual content.

---

## 🧠 Problem Statement

Movie reviews contain valuable opinions but are unstructured text.

This project applies **Deep Learning (LSTM)** to automatically understand sentiment from reviews and predict whether the sentiment is positive or negative.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)

---

## 📂 Dataset

- **IMDB Movie Reviews Dataset**
- 50,000 labeled reviews
    - 25,000 training samples
    - 25,000 testing samples
- Labels:
    - `1` → Positive
    - `0` → Negative

---

## 🔄 Workflow

1. Load and explore IMDB dataset
2. Text preprocessing:
    - Tokenization
    - Padding sequences
3. Build LSTM model
4. Train the model
5. Evaluate performance
6. Predict sentiment for new reviews

---

## 🏗️ Model Architecture

- Embedding Layer
- LSTM Layer
- Dense Output Layer with Sigmoid activation

This architecture helps capture **context and long-term dependencies** in text data.

---

## 📈 Results

- The LSTM model achieves **good accuracy** on test data
- Performs well in distinguishing positive and negative sentiments

(Exact accuracy can be seen by running the notebook.)

---

## ▶️ How to Run

1. Clone the repository
    
    ```bash
    gitclone <repository-url>
    
    ```
    
2. Open the notebook:
    
    ```bash
    jupyter notebook IMDB_reviews_Sentiment_Analysis_LSTM.ipynb
    
    ```
    
3. Run all cells sequentially

---

## ✨ Sample Prediction

Input:

```
"This movie was fantastic. I loved the performances!"

```

Output:

```
Positive

```

---

## 📌 Use Cases

- Movie review analysis
- Social media sentiment analysis
- Product review classification
- Opinion mining systems

---

## 🚀 Future Improvements

- Use **Bidirectional LSTM**
- Add **Dropout** for better generalization
- Try **GRU** or **Transformer-based models**
- Improve preprocessing with lemmatization
