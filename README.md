# Fake_News_Detector
Fake News Detection System using Machine Learning and NLP

Project Description

This project is a Fake News Detection System developed using Natural Language Processing (NLP) and Machine Learning.
It classifies news headlines as Real News or Fake News.
The system can also fetch live news using NewsAPI and analyze it automatically.

Features

Detects fake and real news headlines.
Uses NLP for text processing.
Uses Machine Learning for classification.
Supports live news fetching using NewsAPI.
User can input any news headline for prediction.

Technologies Used

Python,
Pandas,
NLTK,
Scikit-learn,
Requests,
NewsAPI,
Jupyter Notebook

Installation & Setup

Step 1: Install required libraries

pip install pandas nltk scikit-learn requests

Step 2: Get NewsAPI Key

Go to: https://newsapi.org
Create an account and get your API key.

Step 3: Set API Key as Environment Variable

For Windows:
setx NEWS_API_KEY "your_api_key_here".
⚠ Replace your_api_key_here with your own API key.
Then restart Jupyter Notebook.

Step 4: Run the Project

Open Jupyter Notebook,
Open Fake_News_Detection.ipynb,
Run all cells,
Enter any news headline to get prediction.

Output Example

Enter a news headline: Aliens landed in Delhi last night.
Prediction: FAKE NEWS

Developed By

Kirti Dandre
EDUNET Foundation Project– Fake News Detection using NLP

Important Note
For security reasons, API keys are not included in this repository.
Each user must use their own API key.
