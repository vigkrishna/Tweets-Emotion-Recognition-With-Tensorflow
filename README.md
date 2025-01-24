# Tweet Emotion Recognition with TensorFlow

## Overview
This project aims to classify emotions expressed in tweets using a deep learning model built with TensorFlow. Users can input text and receive predictions on the emotion conveyed.

## Features
- Preprocessing of tweet text data
- Deep learning model using TensorFlow and Keras
- Emotion classification into predefined categories
- Deployment using Streamlit for an interactive user interface

## Dataset
The dataset used for training the model contains tweets labeled with emotions such as:
- Anger
- Joy
- Sadness
- Fear
- Surprise
- Love

## Model Details
- **Framework:** TensorFlow
- **Max sequence length:** 50 (for text preprocessing)
- **Embedding:** Pretrained word embeddings or custom embeddings
- **Architecture:** LSTM/GRU-based deep learning model
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam

## Deployment
The model can be deployed using Streamlit to provide an interactive web-based interface for users to input tweets and receive emotion predictions in real-time.

## Acknowledgments
This project was inspired by the Coursera course "Tweet Emotion Recognition with TensorFlow."

## License
This project is licensed under the MIT License.


