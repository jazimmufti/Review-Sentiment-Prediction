<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Review Sentiment Prediction using Count Vectorization and Logistic Regression</h1>
    <section>
        <h2>Project Overview</h2>
        <p>
            This project performs sentiment analysis on textual reviews using machine learning techniques.
            The goal is to predict whether a review is positive or negative based on its text content.
        </p>
    </section>
    <section>
        <h2>Libraries Used</h2>
        <ul>
            <li><code>pandas</code> and <code>numpy</code> for data manipulation</li>
            <li><code>nltk</code> for text preprocessing, including stopwords and stemming</li>
            <li><code>re</code> for regular expression-based text cleaning</li>
            <li><code>sklearn</code> for machine learning models like Logistic Regression and CountVectorizer</li>
        </ul>
    </section>
    <section>
        <h2>Data Collection and Preprocessing</h2>
        <p>
            The dataset consists of textual reviews. Text preprocessing includes:
        </p>
        <ul>
            <li>Cleaning text using regular expressions</li>
            <li>Converting text to lowercase</li>
            <li>Removing stopwords and stemming words</li>
            <li>Creating a corpus for model training</li>
        </ul>
    </section>
    <section>
        <h2>Model Building</h2>
        <p>
            The processed text data is transformed using <code>CountVectorizer</code> into numerical features.
            Logistic Regression is then used to classify reviews as positive or negative.
        </p>
    </section>
    <section>
        <h2>Evaluation</h2>
        <p>
            Model performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. 
            A confusion matrix can also be used to analyze the distribution of correct and incorrect predictions.
        </p>
    </section>
    <section>
        <h2>Usage</h2>
        <p>
            1. Preprocess your review dataset.<br>
            2. Transform the dataset using CountVectorizer.<br>
            3. Train Logistic Regression model.<br>
            4. Predict sentiment for new reviews.
        </p>
    </section>
    <section>
        <h2>Conclusion</h2>
        <p>
            This project demonstrates how machine learning can be applied to text data to predict sentiment. 
            Logistic Regression combined with CountVectorizer provides a simple yet effective approach for sentiment analysis tasks. 
            The methodology can be extended to larger datasets or more advanced models like TF-IDF or neural networks for improved performance.
        </p>
    </section>
    <section>
        <h2>References</h2>
        <ul>
            <li><a href="https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction">Scikit-learn: Text feature extraction</a></li>
            <li><a href="https://www.nltk.org/">NLTK: Natural Language Toolkit</a></li>
        </ul>
    </section>
</body>
</html>
