# Customer-Review-Analyzer
# 🛍️ Customer Review Analyzer

## 📌 Overview

The **Customer Review Analyzer** is an AI-powered Natural Language Processing (NLP) application that analyzes customer reviews and identifies whether the feedback is **positive or negative**.

The system uses a pre-trained **DistilBERT sentiment analysis model** from Hugging Face Transformers. A simple **Gradio interface** allows users to enter a customer review and instantly receive the predicted sentiment and confidence score.

## 🎯 Objectives

* To analyze customer feedback automatically.
* To understand Sentiment Analysis using NLP.
* To use a pre-trained Transformer model.
* To classify reviews as positive or negative.
* To display the prediction with a confidence score.
* To create an easy-to-use web application using Gradio.

## 🛠️ Technologies Used

* **Python**
* **Natural Language Processing (NLP)**
* **Hugging Face Transformers**
* **DistilBERT**
* **PyTorch**
* **Gradio**
* **Google Colab**

## ⚙️ How It Works

1. The user enters a customer review.
2. The review is passed to the sentiment analysis model.
3. DistilBERT analyzes the text.
4. The model predicts the sentiment.
5. The application displays the predicted result and confidence score.

## ✨ Features

* 📝 Customer review input
* 🤖 AI-based sentiment analysis
* 😊 Positive review detection
* 😞 Negative review detection
* 📊 Confidence score
* 🌐 Interactive Gradio interface
* ☁️ Google Colab support
* 🚀 Simple and beginner-friendly

## 🧪 Example

### Positive Review

**Input:**

```text
The product quality is excellent. I really liked it and the delivery was very fast.
```

**Output:**

```text
😊 Positive

📊 Confidence: 99.85%

🏷️ Model Label: POSITIVE
```

### Negative Review

**Input:**

```text
The product was damaged and the delivery was very late.
```

**Output:**

```text
😞 Negative

🏷️ Model Label: NEGATIVE
```

*The confidence score may vary depending on the model and input.*

## ▶️ How to Run

### Step 1: Open Google Colab

Create a new notebook in Google Colab.

### Step 2: Add the Code

Copy the complete Customer Review Analyzer code into one cell.

### Step 3: Run the Code

Click the **Run ▶** button and wait for the required libraries and model to load.

### Step 4: Open the Application

After execution, Gradio will provide a web link.

### Step 5: Analyze a Review

Enter a customer review and click:

**🔍 Analyze Review**

The sentiment and confidence score will be displayed.

## 📂 Project Structure

```text
Customer-Review-Analyzer/
│
├── customer_review_analyzer.ipynb
└── README.md
```


