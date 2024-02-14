# Emoji Prediction using LSTM and GloVe Embeddings

This project aims to predict the emoji associated with a given sentence using LSTM (Long Short-Term Memory) neural networks and pre-trained GloVe (Global Vectors for Word Representation) word embeddings.

## Project Overview

The model is trained on a dataset containing sentences with associated emojis. The sentences are tokenized and converted into word embeddings using pre-trained GloVe word vectors. The LSTM model is then trained on the input sentences to predict the associated emoji. The model is evaluated on a test dataset to measure its performance.

## Usage

To use this repository:

1. Clone the repository

git clone https://github.com/nhan-ngo-usf/emoji-prediction.git

2. Install the required packages:

pip install -r requirements.txt or pip3 install -r requirements.txt

3. Download the pre-trained GloVe word embeddings from the following link:

https://www.kaggle.com/watts2/glove6b50dtxt

4. Run the model on your dataset or utilize the provided scripts for training and testing the model:

## Results
![Accuracy](https://github.com/nhan-ngo-usf/emoji-prediction/assets/65501976/68905446-f94e-4cbb-906d-36f713d2daa3)
![Loss](https://github.com/nhan-ngo-usf/emoji-prediction/assets/65501976/1fe7ebe9-43b3-469d-a712-0058a2fa3321)
