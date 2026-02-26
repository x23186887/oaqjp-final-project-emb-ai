# Final Project

# Emotion Detector 

An AI-powered web application that detects emotions from text using IBM Watson NLP library and Flask.

## 📋 Project Overview

This project was built as a final project for the IBM AI Application Development course. It analyzes text input and identifies the following emotions:
- Anger
- Disgust
- Fear
- Joy
- Sadness

It also identifies the **dominant emotion** from the text.

##  Technologies Used

- Python 3
- IBM Watson NLP Library
- Flask (Web Framework)
- HTML/CSS/JavaScript
- PyLint (Static Code Analysis)
- unittest (Unit Testing)

##  Project Structure
```
oaqjp-final-project-emb-ai/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── templates/
│   └── index.html
│
├── static/
├── server.py
├── test_emotion_detection.py
└── README.md
```

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOURUSERNAME/oaqjp-final-project-emb-ai.git
cd oaqjp-final-project-emb-ai
```

### 2. Install dependencies
```bash
pip install flask requests
```

### 3. Run the Flask server
```bash
python3 server.py
```

### 4. Open in browser
```
http://localhost:5000
```

##  Run Unit Tests
```bash
python3 -m unittest test_emotion_detection.py -v
```

## 📊 Run Static Code Analysis
```bash
pylint EmotionDetection/emotion_detection.py
pylint server.py
```

##  Tasks Completed

- Task 1: Cloned the project repository
- Task 2: Created emotion detection application using Watson NLP
- Task 3: Formatted the output of the application
- Task 4: Packaged the application
- Task 5: Ran unit tests (5/5 passed)
- Task 6: Web deployment using Flask
- Task 7: Incorporated error handling
- Task 8: Static code analysis (10/10 score)

##  Author

Amritha  
