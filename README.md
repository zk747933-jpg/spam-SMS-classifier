# 📩 SMS / Email Spam Classifier

A Machine Learning web application that classifies messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques.
The app is built using **Python**, **Scikit-learn**, and **Streamlit**.

---

## 🚀 Features

* Classifies SMS or Email messages into **Spam** or **Not Spam**
* Uses **TF-IDF Vectorization** for text feature extraction
* Applies **Machine Learning model** for prediction
* **Interactive web interface** built with Streamlit
* Simple and fast message classification

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Scikit-learn
* NLTK
* Pandas
* TF-IDF Vectorizer

---

## 📂 Project Structure

```
sms-spam-classification
│
├── app.py              # Streamlit web application
├── main.py             # Training or helper script
├── model.pkl           # Trained ML model
├── vectorizer.pkl      # TF-IDF vectorizer
├── requirements.txt    # Required libraries
└── README.md           # Project documentation
```

---

## ⚙️ Installation

Clone the repository:

```
https://github.com/zk747933-jpg/spam-SMS-classifier
```

Navigate to the project folder:

```
cd sms-spam-classification
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app:

```
streamlit run app.py
```

The application will open in your browser.

---

## 🌐 Live Demo / Deployment

You can try the live application here:

```
https://spam-sms-clacifier-babcaumsavegtqibm7hb82.streamlit.app/
```

Replace the above link with your deployed application link.

---

## 🧠 How It Works

1. User enters an SMS or email message.

2. The message is preprocessed:

   * Lowercasing
   * Tokenization
   * Removing stopwords
   * Stemming

3. The text is converted into numerical features using **TF-IDF Vectorizer**.

4. The trained machine learning model predicts whether the message is **Spam** or **Not Spam**.

---

## 📊 Example

Input:

```
Congratulations! You have won a free lottery ticket.
```

Output:

```
Spam
```

---

## 👨‍💻 Author

**Zishan Khan**

Aspiring **Data Scientist / Machine Learning Engineer**

---

## ⭐ If you like this project

Give it a **star ⭐ on GitHub**
