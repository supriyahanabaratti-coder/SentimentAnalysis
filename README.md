# SentimentAnalysis

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SUPRIYA SUNIL HANABARATTI

*INTERN ID*: CTIS7712

*DOMAIN*: DATA ANALYST

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

 **Project Description: Sentiment Analysis Using NLP**

Sentiment Analysis is a widely used Natural Language Processing (NLP) technique that focuses on identifying and extracting opinions or emotions expressed in textual data. In today’s digital world, a massive amount of text data is generated every second through social media platforms, online reviews, blogs, and customer feedback. Understanding the sentiment behind this data is very important for businesses and organizations to make better decisions. This project aims to perform sentiment analysis on textual data such as product reviews or short messages and classify them into categories like positive, negative, or neutral.

The main objective of this project is to build a machine learning model that can automatically analyze text and determine the sentiment expressed in it. The project begins with collecting or creating a dataset containing sample text data along with corresponding sentiment labels. In this implementation, a simple dataset of sentences is used for demonstration purposes, where each sentence is labeled as positive, negative, or neutral. This makes it easier to understand the workflow of sentiment analysis before applying it to larger real-world datasets.

The next step in the project is data preprocessing, which is a crucial part of any NLP task. Raw text data often contains noise such as punctuation marks, special characters, and unnecessary words that do not contribute to the meaning. To clean the data, several preprocessing techniques are applied. These include converting all text to lowercase, removing non-alphabetic characters, eliminating stopwords (commonly used words like “the”, “is”, “and”), and applying stemming to reduce words to their root form. This process helps in improving the performance of the model by focusing only on meaningful words.

After preprocessing, the cleaned text data is converted into numerical format using the TF-IDF (Term Frequency–Inverse Document Frequency) vectorization technique. Machine learning models cannot directly understand text, so this step transforms textual data into a matrix of numerical features. TF-IDF not only considers how frequently a word appears in a document but also reduces the importance of words that appear frequently across all documents, thereby improving the quality of features.

Once the data is transformed, it is divided into training and testing sets. The training set is used to train the machine learning model, while the testing set is used to evaluate its performance. In this project, a Logistic Regression model is used for classification. Logistic Regression is a simple yet effective algorithm for text classification tasks and works well for smaller datasets.

The trained model is then used to predict the sentiment of unseen data. The performance of the model is evaluated using metrics such as accuracy and classification report, which includes precision, recall, and F1-score. Additionally, a confusion matrix is used to visualize how well the model is performing in terms of correct and incorrect predictions. Data visualization techniques like bar charts are also used to show the distribution of sentiment classes in the dataset.

Finally, the model is tested with custom input sentences to demonstrate its practical use. Users can input any sentence, and the model will predict whether the sentiment is positive, negative, or neutral. This shows how sentiment analysis can be applied in real-life scenarios such as analyzing customer feedback, monitoring brand reputation, or understanding public opinion.

**OUTPUT**



In conclusion, this project successfully demonstrates the implementation of sentiment analysis using NLP techniques and machine learning. It highlights the importance of data preprocessing, feature extraction, and model evaluation. The project can be further improved by using larger datasets, advanced models like Naive Bayes or Support Vector Machines, or even deep learning techniques for better accuracy and performance.
