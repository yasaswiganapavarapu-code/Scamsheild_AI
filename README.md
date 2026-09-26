# Scamsheild_AI
ScamShield AI

An AI-based SMS scam and spam message detection system designed to help identify potentially suspicious messages.

Overview

ScamShield AI uses machine learning and natural language processing techniques to classify SMS messages as spam or ham (legitimate).

The project explores how AI can be used to automate the detection of potentially harmful or unwanted messages and provide users with a simple way to assess suspicious content.

Features

- SMS message classification
- Text preprocessing and data cleaning
- TF-IDF-based text feature extraction
- Logistic Regression machine learning model
- Prediction of new messages
- Confidence/risk information for predictions
- Dataset validation and preprocessing scripts

Technologies Used

- Python
- Machine Learning
- Natural Language Processing (NLP)
- Scikit-learn
- TF-IDF
- Logistic Regression
- Pandas

Dataset

The project uses the SMS Spam Collection dataset containing 5,574 labelled SMS messages.

The messages are classified into:

- Ham — legitimate messages
- Spam — unwanted or potentially fraudulent messages

Project Structure

Scamshield_AI/
│
├── dataset/
├── app.py
├── check_dataset.py
├── clean_data.py
├── predict_message.py
├── train_model.py
└── README.md

How It Works

1. The SMS dataset is checked and cleaned.
2. Text messages are converted into numerical features using TF-IDF.
3. A Logistic Regression model is trained on the processed data.
4. The trained model is used to classify new messages.
5. The application provides a prediction for the entered message.

Model Performance

The current implementation achieved approximately 97.44% accuracy on the evaluated dataset.

Purpose

This project was developed as a practical exploration of applying AI and machine learning to a real-world problem: helping users identify suspicious SMS messages.

Future Improvements

- Add more recent scam-message datasets
- Improve detection of phishing and social-engineering messages
- Add multilingual message detection
- Develop a more user-friendly web interface
- Explore additional machine learning and deep learning models

Author

Ganapavarapu Yasaswi
