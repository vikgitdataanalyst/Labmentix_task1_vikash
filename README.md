# Labmentix_task1_vikash
Hello! viewers, welcome to my github profile

The Deep CSAT project focuses on building a deep learning model to predict customer satisfaction based on textual customer feedback. The goal is to classify sentiments and understand service quality using a clean, processed dataset and a neural network-based approach. Here's a breakdown of the project pipeline.

Loaded a .csv file containing customer remarks and related metadata using pandas, inspected the dataset structure, dimensions, and column types.

Removed irrelevant columns that do not contribute to the analysis, handled missing and null values by either dropping or imputing based on column context.
Converted data types (e.g., converting price and rating fields to numeric types using astype or pd.to_numeric).

Perform data visualization using seaborn.
Cleaned and transformed the customer_remarks text data:

Lowercased all text, removed punctuation and special characters using regular expressions, tokenized text using nltk.word_tokenize, removed stopwords using nltk.corpus.stopwords.

Encoded categorical output labels using LabelEncoder from scikit-learn.

Applied StandardScaler to numeric features for optimal model performance.

Divided data into training and testing sets using train_test_split.

Built an Artificial Neural Network (ANN) using Keras Sequential API.
1.input layer matching feature shape
2.Hidden layers with ReLU activation
3.Output layer with sigmoid or softmax depending on binary or multi-class
4.Used Dropout to reduce overfitting.

Trained the model using the .fit() method.
Evaluated model performance on test data using .evaluate() and accuracy metrics.


