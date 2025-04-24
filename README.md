#  IMDb Sentiment Analysis

A comprehensive sentiment analysis project using Machine Learning and Deep Learning techniques to classify movie reviews as **positive** or **negative**.

---

##  Project Structure
IDMB Sentiment Analysis/
├── IMDb_Sentiment_Analysis.ipynb     
├── requirements.txt                  
├── train.csv                        
├── models/                           
│   ├── sentiment_analysis_model.pkl 
│   └── tfidf_vectorizer.pkl         
└── visuals/                         
    ├── confusion matrix.png          
    └── LSTM Training plot.png       

## Features

- **Text Preprocessing**: Cleaning, stopword removal, tokenization
- **TF-IDF Vectorization** for feature extraction
- **Logistic Regression** with Hyperparameter Tuning (`GridSearchCV`)
- **Deep Learning** with an LSTM model using Keras
- **Model Evaluation**: Accuracy, precision, recall, F1, confusion matrix
- **Visualization**: Confusion matrix & training performance plots

- ##  Dataset

- File: `train.csv`
- Source: IMDb movie reviews (50,000 labeled samples)
- Format: `review`, `sentiment`

>  Due to file size constraints on GitHub, `train.csv` may not be uploaded directly. Consider [downloading it here](https://ai.stanford.edu/~amaas/data/sentiment/) or storing it via Google Drive/Git LFS.

---

##  Requirements

Install all dependencies via:

```bash
pip install -r requirements.txt

## How to run

Clone the repository:
git clone https://github.com/lakshit2234/IDMB-Sentiment-Analysis.git

Navigate into the folder:
cd IDMB-Sentiment-Analysis

Install dependencies:
pip install -r requirements.txt

Run the notebook: Open IMDb_Sentiment_Analysis.ipynb in Jupyter or VS Code.

## Results
Logistic Regression Accuracy (Tuned): ~88%

LSTM Test Accuracy: ~90%

## Visualizations:

Confusion matrix

LSTM training accuracy & loss plot

 Models Saved
sentiment_analysis_model.pkl: Best logistic regression model

tfidf_vectorizer.pkl: Fitted TF-IDF vectorizer for predictions

## Contact
Made by Lakshit Saini
