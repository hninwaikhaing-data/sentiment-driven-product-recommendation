# Sentiment-Driven Product Recommendation and Sales Insight System

## Overview
The Sentiment-Driven Product Recommendation and Sales Insight System is an end-to-end data science project that leverages **Natural Language Processing (NLP)**, **machine learning**, and **interactive visualization** to improve product recommendations and business insights in e-commerce platforms.

Customer reviews contain valuable information about product quality, user satisfaction, and purchasing behavior. However, these reviews are unstructured and difficult to analyze at scale. This project addresses that challenge by transforming raw customer reviews into structured sentiment insights that support **data-driven recommendations, sales analysis, and strategic decision-making**.

The system integrates sentiment classification models with a web-based dashboard to provide both technical evaluation and business-focused insights.


## Project Goals
- Extract and analyze sentiment from customer product reviews
- Classify reviews into positive, negative, and neutral sentiment categories
- Compare multiple machine learning algorithms for sentiment classification
- Enhance product recommendation logic using sentiment scores
- Visualize sentiment trends and product performance through interactive dashboards
- Deliver actionable insights for business and marketing stakeholders

## Analytical Approach

### 1. Data Collection
- Product review dataset sourced from an e-commerce platform (Amazon-style reviews)
- Includes review text, ratings, and product-related attributes

### 2. Data Preprocessing
- Text normalization and cleaning
- Tokenization and stopword removal
- Feature extraction using **TF-IDF vectorization**
- Sentiment polarity scoring

### 3. Sentiment Classification Models
The following supervised machine learning models were implemented and evaluated:
- **Logistic Regression**
- **Naïve Bayes**
- **Support Vector Machine (SVM)**

These models were selected for their effectiveness in text classification, interpretability, and computational efficiency.

### 4. Model Evaluation
Model performance was assessed using:
- Accuracy
- Precision
- Recall
- F1-score

Comparative evaluation helps identify the most suitable model for sentiment-based recommendation systems.

### 5. Recommendation & Insight Generation
- Sentiment scores are integrated with product data
- Products are ranked and analyzed based on sentiment distribution
- Insights support recommendation improvement and sales strategy

### 6. Visualization & Dashboard
- Interactive dashboards developed using web technologies
- Displays sentiment trends, product performance, and review insights
- Designed for both technical and non-technical users


## System Architecture
The system follows a modular and scalable architecture:

- **Data Layer**  
  Raw reviews and processed sentiment data

- **Model Layer**  
  Machine learning models for sentiment classification

- **Backend Layer**  
  Flask-based API for processing requests and serving results

- **Frontend Layer**  
  Interactive dashboard for visualization and exploration

## Technology Stack

### Programming & Frameworks
- Python
- Flask
- JavaScript

### Data Science & NLP
- pandas
- NumPy
- scikit-learn
- TextBlob
- TF-IDF Vectorization

### Machine Learning
- Logistic Regression
- Naïve Bayes
- Support Vector Machine (SVM)

### Visualization & Frontend
- HTML
- CSS
- JavaScript (Chart.js / D3.js)


---

## Key Features
- Automated sentiment classification of customer reviews
- Comparative evaluation of multiple ML algorithms
- Sentiment-driven product ranking and recommendation logic
- Interactive dashboards for sentiment and sales insights
- Business-oriented insights derived from customer feedback

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Sentiment-product-Recommendation-System.git

