# Sentiment Analysis with LSTM

This project demonstrates sentiment analysis using an LSTM network, incorporating TF-IDF and word embeddings for text classification.

## Requirements

- Python 3.7+
- TensorFlow 2.0+
- Numpy
- Pandas
- Scikit-learn
- NLTK
- Gensim
- Matplotlib

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/sentiment-analysis-lstm.git
    cd sentiment-analysis-lstm
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preparation**: Prepare the dataset.

    ```bash
    python src/data_preprocessing.py
    ```

2. **Model Training**: Train the LSTM model.

    ```bash
    python src/train.py
    ```

3. **Evaluation**: Evaluate the model performance.

    ```bash
    python src/evaluate.py
    ```
