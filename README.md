**Spam SMS Classifier**

**Overview**

This project focuses on developing a machine learning-based Spam SMS Classifier. The goal is to create a model capable of distinguishing between spam and legitimate text messages. 
The project includes a Streamlit web application that provides an interactive interface for users to test the classifier in real-time.

**Features**

Machine Learning Model: Utilizes Natural Language Processing (NLP) and classification algorithms to train a model on a labeled dataset of spam and non-spam SMS messages.

Streamlit App: An interactive web application built with Streamlit, allowing users to input a text message and receive instant classification results.

Real-Time Classification: Users can test the model on-the-fly by entering text messages into the app and observing the spam classification results.

Performance Metrics: The app displays key performance metrics, such as accuracy, precision, recall, and F1 score, providing insights into the model's effectiveness.

Visualizations: Incorporates visualizations like confusion matrices or ROC curves to help users understand the model's performance visually.

**Project Structure**

app.py: Main file for the Streamlit app.

model_training.ipynb: Jupyter Notebook for training and evaluating the machine learning model.

data/: Directory containing the dataset used for model training.

requirements.txt: List of project dependencies.
