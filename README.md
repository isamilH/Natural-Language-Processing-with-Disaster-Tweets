# Natural-Language-Processing-with-Disaster-Tweets
This project aims to predict whether a given tweet is about a real disaster or not. The dataset used consists of tweets labeled as either relating to a disaster (1) or not (0). The task is a binary classification problem using various natural language processing (NLP) techniques and machine learning models.
## Key Steps
- Data Loading and Preprocessing:
        Missing values in keyword and location are handled.
        Text cleaning involves lowercasing, removing URLs, and removing special characters.
- Text Vectorization:
        Tokenization and vectorization of text using various approaches like Bag of Words (BoW), Term Frequency-Inverse Document Frequency (TF-IDF), and Word Embeddings (e.g., BERT).
- Modeling:
        The notebook implements a BERT-based classification model using Hugging Face's transformers library.
        Other models like Logistic Regression, SVM, and Neural Networks can also be explored for comparison.
- Model Training:
        The notebook trains a BERT model for tweet classification using a training dataset.
        It logs performance metrics like training loss, validation accuracy, and F1 score.
- Evaluation:
        The trained model is evaluated on the validation set using metrics like F1 Score and Accuracy.
        The results are logged, and the model's performance is visualized.
- Prediction:
        Predictions are made on the test set using the trained model.
