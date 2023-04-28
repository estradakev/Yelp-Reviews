# Yelp-Reviews

This is a university project aimed at predicting business star ratings based on review text. Neural network implementations were used in TensorFlow, and the problem was considered a regression problem. Since it was text-based data, the TF-IDF method was used to clean and extract information, and neural networks with early stopping were created to train the data. The tools used were Pandas, NumPy, scikit-learn, TensorFlow, and Jupyter Notebook/Google Collab. The dataset is from https://www.yelp.com/dataset



## Implementation Details

Two JSON files to create a DataFrame containing information about the business attributes, such as location, name, star ratings, etc. The DataFrames from the reviews and the business attributes were then grouped together.

We also used the Adam and SDG optimizers, along with the sigmoid, tanh, and relu activation functions to train the neural networks.

