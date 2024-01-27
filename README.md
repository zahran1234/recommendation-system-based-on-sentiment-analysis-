# Recommendation System Based on Sentiment Analysis

Welcome to the GitHub repository for our innovative recommendation system that leverages sentiment analysis! This project utilizes a unique approach to recommend options based on user-provided inputs, analyzing reviews scraped from Twitter and other platforms.

## Project Overview

The core idea is to provide recommendations based on sentiment analysis of reviews. Here's how it works:
- Users provide multiple inputs.
- The system scrapes reviews from Twitter and other sources.
- It then classifies these reviews as positive, negative, or neutral.
- A pie chart visually represents the sentiment distribution.
- The system recommends the option with the highest positive-to-negative ratio.

## Key Components

1. **Data Collection**
   - Collected Egyptian language datasets from various sources:
     - Google Maps
     - Twitter
     - Google Play

2. **Data Preprocessing**
   - Implemented standard preprocessing techniques to clean and prepare the data for analysis.

3. **Machine Learning Models**
   - Utilized a range of models to classify sentiments:
     - SVM (Support Vector Machine)
     - LSVM (Linear SVM)
     - KNN (K-Nearest Neighbors)
     - Naive Bayes
     - Decision Tree
     - Random Forest
     - Logistic Regression

4. **Deep Learning Models**
   - Explored advanced deep learning architectures:
     - Forward Neural Network
     - CNN (Convolutional Neural Network)

5. **Sequential Models**
   - Applied models that are effective in processing sequential data:
     - RNN (Recurrent Neural Network)
     - GRU (Gated Recurrent Unit)
     - LSTM (Long Short-Term Memory)

## Special Features

- **Transfer Learning**: Integrated "CAML", a pre-trained model based on Arabic sentiment analysis, using Transformer architectures.
- **Scraping**: Employed Twitter API for dynamic review scraping based on user input.
- **User Interface**: Developed a user-friendly GUI using Streamlit, which simplifies interaction without the need for complex web development.

## How to Use

To explore the recommendation system, you can access the tool through this link: [Google Drive - Recommendation System](https://drive.google.com/file/d/19umMJi7bjy_KA1geRcfzCv5_BfRgpU7b/view?usp=sharing).

## Get Involved

Your contributions and suggestions are welcome! Whether it's improving the algorithms, enhancing the user interface, or adding new data sources, feel free to fork this repository or reach out with your ideas.

## Conclusion

This project represents a significant step in sentiment analysis and recommendation systems, especially focusing on Arabic language data. It's a testament to the power of machine learning and natural language processing in deriving meaningful insights from complex datasets.

Thank you for visiting, and we hope you find this project as exciting as we do!
