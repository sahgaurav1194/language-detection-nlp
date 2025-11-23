# 🚀 Language Detection Model (NLP + Machine Learning)

This project is an end-to-end **Language Detection System** built using **Python**, **NLP preprocessing**, and a **Multinomial Naive Bayes classifier**.
It predicts the language of any input sentence — similar to the *auto-detect* feature used in Google Translate.

This project demonstrates practical skills in:

* Data cleaning & preprocessing
* NLP feature extraction (CountVectorizer)
* Machine Learning model building
* Model evaluation
* Real-time text prediction

---

## 📌 Features

✔ Detects the language of any input text
✔ Preprocesses raw text (cleaning, tokenization)
✔ Converts text into numerical vectors
✔ Trains a Naive Bayes classifier
✔ Provides real-time predictions in terminal or notebook
✔ Ready for deployment (Flask API / Render / AWS)

---

## 🧠 Tech Stack

* **Python**
* **Scikit-learn**
* **Pandas, NumPy**
* **NLP (CountVectorizer, tokenization, stopword removal)**
* **Multinomial Naive Bayes**
* **Jupyter/Colab (for training)**

---

## 📂 Project Structure

```
language-detection/
│
├── language_detection_model.py      # Main ML code
├── requirements.txt                 # Dependencies
└── README.md                        # Project documentation
```

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run the Model

Run the Python file:

```bash
python language_detection_model.py
```

You will be prompted to enter a sentence, for example:

```
Enter text: Hola amigo
Predicted Language: Spanish
```

---

## 🧪 Model Workflow

1. **Load dataset**
2. **Clean text**:

   * Remove special characters
   * Convert to lowercase
   * Strip extra spaces
3. **Tokenization**
4. **Feature extraction using CountVectorizer**
5. **Train Multinomial Naive Bayes**
6. **Evaluate performance**
7. **Real-time prediction**

---

## 📈 Why Naive Bayes?

Naive Bayes is ideal for:

* Text classification
* High-dimensional sparse data
* Fast training and prediction
* Baseline NLP models

It often performs surprisingly well for language detection.

---

## 🌐 Deployment (Optional Upgrades)

This project can be deployed as:

* A **Flask API**
* A **Render Web Service**
* An **AWS Elastic Beanstalk app**


## 🚀 Future Improvements

* Add more languages to dataset
* Integrate TF-IDF
* Use deep learning (LSTM/GRU/Transformer)
* Add confusion matrix & metrics
* Build a Streamlit web app
* Deploy on cloud platforms

---

## 👤 Author

**Gaurav Sah**
ML Data Associate • Aspiring Data Scientist
📍 Bangalore, India
# language-detection-nlp
