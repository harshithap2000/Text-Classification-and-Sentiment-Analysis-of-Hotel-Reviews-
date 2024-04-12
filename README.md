This repository contains code for sentiment analysis and aspect prediction on hotel reviews. The project aims to predict the overall sentiment of a review and identify specific aspects mentioned, such as cleanliness, location, and service quality.

## Dataset

Follow the link to get the dataset - [Dataset](https://drive.google.com/file/d/1R6nWTkTYX2_8p_Je8fkyU93gSnJNmoah/view?usp=drive_link)

## Requirements

To run the code in this repository, you'll need the following dependencies:

- Python 3.x
- pandas
- numpy
- nltk
- scikit-learn
- matplotlib

You can install the required Python packages using pip:

```
pip install pandas numpy nltk scikit-learn matplotlib
```

Additionally, you'll need to download the necessary NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('vader_lexicon')
```

## Usage

1. Clone the repository or download the code files.
2. Ensure that you have the dataset file in the same directory as the code files or update the file path accordingly.
3. Run the code using a Python environment or a Jupyter Notebook.

The code performs the following tasks:

1. Data loading and preprocessing
2. Exploratory data analysis (EDA)
3. Sentiment analysis using supervised methods (e.g., Naive Bayes)
4. Sentiment analysis using lexicon-based methods (e.g., VADER)
5. Aspect prediction for hotel reviews

## Methodology

The project implements the following methodologies:

1. **Sentiment Analysis**: The code includes techniques for sentiment analysis using supervised machine learning methods (e.g., Naive Bayes) and lexicon-based methods (e.g., VADER). The sentiment analysis models are trained on the provided dataset and evaluated using appropriate metrics.

2. **Aspect Prediction**: The code proposes a methodology for predicting various aspects of hotels, such as cleanliness, location, and service quality, based on the review text. This involves extracting aspect-related keywords and phrases, applying natural language processing techniques (e.g., sentiment analysis, topic modeling), and training supervised machine learning models to predict aspect ratings.
