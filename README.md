# 🍽️ Sentiment Analysis Workflow (n8n)

An intelligent automation workflow built with **n8n** that collects customer feedback, analyzes sentiment using AI, and stores structured results directly in **Google Sheets**.

---

## 🚀 Overview

This workflow helps restaurants automatically collect and analyze customer reviews in a simple and efficient way.

Customers submit feedback through a form, and the system processes it to extract meaningful insights such as:

- Customer Information (Name, Email, Phone)
- Review Text
- Sentiment (Positive / Negative / Neutral)
- Confidence Score (%)

The final structured data is stored in Google Sheets for easy tracking and analysis.

---

## ⚙️ Workflow Structure

The workflow operates in the following sequence:

### 1. 📝 Form Submission Trigger
- Collects customer data:
  - Name
  - Email
  - Phone Number
  - Review
  - Date
- Acts as the entry point of the workflow

---

### 2. 🤖 AI Agent (Sentiment Analysis)
- Uses a structured **system prompt**
- Analyzes the customer review
- Generates:
  - Sentiment classification:
    - Positive
    - Negative
    - Neutral
  - Confidence score (percentage)

---

### 3. 🧠 Code (JavaScript)
- Processes AI output
- Extracts:
  - Sentiment label
  - Percentage score
- Cleans and formats data for storage

---

### 4. 📊 Google Sheets (Append Row)
- Stores all processed data
- Each row includes:
  - Customer details
  - Review
  - Sentiment result
  - Confidence score
- Acts as a lightweight database

---

## 💡 Use Case

This system enables restaurants to:

- Monitor customer satisfaction in real-time
- Identify trends in feedback
- Make data-driven decisions
- Eliminate manual review analysis

---

## 🧩 Tech Stack

- **n8n** – Workflow automation
- **AI Agent (LLM)** – Sentiment analysis
- **JavaScript** – Data processing
- **Google Sheets** – Data storage

---

## 📈 Key Features

- Fully automated workflow
- Real-time sentiment analysis
- Structured data extraction
- Scalable and easy to customize
- No-code / low-code implementation

---

## 🛠️ How It Works

1. User submits a review via form  
2. Data is sent to AI Agent  
3. AI analyzes sentiment  
4. JavaScript formats output  
5. Data is stored in Google Sheets  

---

## 🎯 Conclusion

This project demonstrates how **AI + Automation** can be combined using tools like **n8n** to build powerful real-world solutions with minimal effort.

It transforms raw customer feedback into actionable insights automatically.

---
## 🎬 Demo

https://github.com/mohamedmagdy776/Sentiment-Analysis/releases/download/v1.0/Video.mp4

---

## 👤 Author

**Eng Mohamed Magdy Elghandour**
AI Automation Engineer
## 👨‍💻 Author
