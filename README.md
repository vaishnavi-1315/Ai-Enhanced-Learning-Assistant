# 🤖 AI-Enhanced Question Answer Generation and Evaluation System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![NLP](https://img.shields.io/badge/NLP-NLTK%20%7C%20Scikit--Learn-green)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📖 Overview

The **AI-Enhanced Question Answer Generation and Evaluation System** is
an intelligent web application that automates question generation and
answer evaluation using Artificial Intelligence (AI), Natural Language
Processing (NLP), and Machine Learning.

The system allows users to upload textual content, generate objective
and subjective questions, evaluate answers using **TF-IDF
Vectorization** and **Cosine Similarity**, and generate PDF reports.
Built with **Python**, **Flask**, **MySQL**, **NLTK**, and
**Scikit-learn**, it provides an efficient and scalable solution for
modern educational assessment.

------------------------------------------------------------------------

## ✨ Features

-   User Registration & Login
-   Secure Authentication
-   Profile Management
-   Upload Text Documents
-   Objective Question Generation
-   Subjective Question Generation
-   NLP-based Text Processing
-   Automated Answer Evaluation
-   TF-IDF + Cosine Similarity Scoring
-   PDF Report Generation
-   MySQL Database Integration
-   Responsive Web Interface

------------------------------------------------------------------------

## 🛠️ Technology Stack

  Category           Technologies
  ------------------ -----------------------
  Backend            Python, Flask
  Frontend           HTML, CSS, JavaScript
  Database           MySQL
  NLP                NLTK
  Machine Learning   Scikit-learn
  PDF                pdfkit
  File Handling      werkzeug
  Model Loading      pickle

------------------------------------------------------------------------

## 🏗️ System Architecture

``` text
User
  │
  ▼
Flask Web Application
  │
  ├── Authentication
  ├── File Upload
  ├── Question Generation
  ├── Answer Evaluation
  ├── PDF Report
  │
  ▼
MySQL Database
```

------------------------------------------------------------------------

## 🔄 Workflow

``` mermaid
flowchart TD
A[User Login] --> B[Upload Document]
B --> C[Text Preprocessing]
C --> D[Question Generation]
D --> E[Answer Submission]
E --> F[TF-IDF Vectorization]
F --> G[Cosine Similarity]
G --> H[Score Generation]
H --> I[PDF Report]
```

------------------------------------------------------------------------

## 📂 Project Structure

``` text
AI-Enhanced-QA-System/
│── app.py
│── templates/
│── static/
│── uploads/
│── database/
│── models/
│── utils/
│── requirements.txt
└── README.md
```

------------------------------------------------------------------------

## 🚀 Installation

``` bash
git clone https://github.com/yourusername/AI-Enhanced-QA-System.git
cd AI-Enhanced-QA-System
python -m venv venv
```

Activate the environment:

**Windows**

``` bash
venv\Scripts\activate
```

**Linux/macOS**

``` bash
source venv/bin/activate
```

Install dependencies:

``` bash
pip install -r requirements.txt
```

Run:

``` bash
python app.py
```

Open:

    http://127.0.0.1:5000

------------------------------------------------------------------------

## 📸 Screenshots

Create a folder named **screenshots** and add images such as:

-   Login
-   Dashboard
-   Upload Dataset
-   Question Generation
-   Answer Evaluation
-   PDF Report
------------------------------------------------------------------------

## 🎯 Applications


-   Colleges & Universities
-   Online Assessments
-   Training Institutes
-   Personalized Learning

------------------------------------------------------------------------

## 🔮 Future Enhancements

-   Transformer-based Question Generation
-   BERT/Sentence-BERT Evaluation
-   Multilingual Support
-   Adaptive Learning
-   AI Chat Assistant
-   Cloud Deployment

------------------------------------------------------------------------

## 🤝 Contributing

Contributions are welcome through Issues and Pull Requests.

------------------------------------------------------------------------

## 📄 License

This project is licensed under the MIT License.

------------------------------------------------------------------------

## 👩‍💻 Author

**Vaishnavi**

If you like this project, consider giving it a ⭐ on GitHub.
