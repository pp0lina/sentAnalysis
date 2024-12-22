**Sentiment Analysis Project for Film Reviews**

**Overview**

This project implements a **sentiment analysis system** designed to classify movie reviews as either **positive** or **negative**. Various NLP techniques were used to preprocess text data, train models, and evaluate performance.

* * * * *

**Features**

-   **Data Collection**: The data used for training the model was sourced from Kaggle <https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews>
-   **Preprocessing**:

-   Conversion to lowercase
-   Removal of stop words
-   Lemmatization
-   Tokenization

-   **Machine Learning Model**:

-   The DistilBERT model was used for tokenization. After this, it was trained on three datasets of different sizes. The metrics for each model were extracted.

-   **Evaluation Metrics used**:

-   Accuracy, Precision, Recall, F1-Score, Confusion Matrices

* * * * *

**Requirements**

-   Python 3.8+
-   Essential Libraries:

-   **pandas**
-   **numpy**
-   **scikit-learn**
-   **nltk:** For text preprocessing
-   **transformers** and **torch**: For using DistilBERT
-   **beautifulsoup4** and **requests**: For web scraping

Install dependencies using the provided **requirements.txt** file:

pip install -r requirements.txt

* * * * *

**Example usage**

The code in the Model.ipynb file allows adding a link to the film reviews. It then processes these reviews, predicts their sentiment and determines the overall emotion towards the film, i.e., positive or negative. This can be used to assess audience opinions on films, provide insights for marketing strategies, content recommendations, and customer feedback monitoring.

* * * * *

**Contribution**

Feel free to contribute and submit a pull request if you notice any issues or have some improvements!
