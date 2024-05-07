# Fake News Detector

## Overview

Fake News Detector is a machine learning project designed to identify and classify fake news articles from real ones. The project utilizes natural language processing (NLP) techniques and a logistic regression model to analyze text data and make predictions on the authenticity of news articles.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Web Application](#web-application)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Data Preprocessing**: The project preprocesses text data by removing stopwords, stemming words, and vectorizing text using TF-IDF.
- **Machine Learning Model**: It trains a logistic regression model on the preprocessed data to classify news articles as fake or real.
- **Web Application (Optional)**: Fake News Detector provides a web interface for users to input news articles and receive predictions on their authenticity. Note that Streamlit is required for running the web application, but it is optional for using the core functionality of the project.


## Installation

To install Fake News Detector, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/nayeem329/fake-news-detector.git

2. Navigate to the project directory:

  ```bash
   cd fake-news-detector
  ```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

# Usage
1. Preprocess Data: Run the preprocessing script to clean and prepare the dataset.
```bash
python preprocess.py
```

2. Train Model: Train the logistic regression model using the preprocessed data.
```bash
python train.py
```

3.Run Web Application (Optional): Start the web application to interact with the Fake News Detector.

```bash
streamlit run app.py
```
# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit (Optional)

# Dataset
The project uses the Fake News Dataset, specifically the Train.csv file, which is uploaded directly to this repository. This dataset contains thousands of news articles labeled as either fake or real.

# Preprocessing
The text data is preprocessed by removing stopwords, stemming words, and vectorizing text using TF-IDF (Term Frequency-Inverse Document Frequency) representation.

# Model Training
A logistic regression model is trained on the preprocessed data to classify news articles as fake or real. The model achieves [accuracy] accuracy on the test set.

# Web Application
Fake News Detector provides a web application where users can input news articles and receive predictions on their authenticity.

# Contributing
Contributions are welcome! Here are some ways you can contribute to the project:

- Submit bug reports or feature requests by opening an issue.
- Implement new features or enhancements and submit pull requests.
- Improve documentation and README.

# License
This project is licensed under the MIT License.
