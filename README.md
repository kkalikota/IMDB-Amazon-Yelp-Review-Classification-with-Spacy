# IMDB-Amazon-Yelp-Review-Classification-with-Spacy
Including Negation Handling 

<img src="https://github.com/user-attachments/assets/e02848c2-3b64-4428-8fcb-72f02a3fefe5">

### Project Overview

This project focuses on sentiment analysis using reviews from three prominent datasets: IMDB, Amazon, and Yelp. The goal is to classify reviews as positive or negative, leveraging natural language processing (NLP) techniques to improve the accuracy of the classification model.

### Approach

1. **Data Collection**:
   - Utilized datasets from IMDB, Amazon, and Yelp to gather a diverse set of reviews for training and evaluation.

2. **Data Cleaning**:
   - Removed stopwords and punctuation to streamline the text for analysis.
   - Implemented lemmatization using SpaCy to reduce words to their base forms, enhancing the model's ability to understand the context.

3. **Feature Extraction**:
   - Employed TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to transform the cleaned text into numerical feature vectors, capturing the importance of words in the context of the documents.

4. **Model Selection**:
   - Used the LinearSVC classifier for its efficiency and effectiveness in handling high-dimensional data typical in text classification tasks.

5. **Handling Negation**:
   - Developed a method to <ins>address negation</ins> in reviews (e.g., converting "not good" to a negative sentiment), which significantly improved the accuracy of the model.

6. **Model Evaluation**:
   - Tested the model using real-time data to validate its performance in a practical scenario, ensuring it generalizes well beyond the training datasets.

### Impact

The project demonstrated the following impacts:
- **Enhanced Accuracy**: The inclusion of negation handling led to a notable <ins>**increase in accuracy**</ins>, showcasing the importance of nuanced language processing in sentiment analysis.
- **Real-World Applicability**: By testing with real-time data, the model proved its relevance and adaptability, providing insights into customer sentiments for businesses or researchers.
- **Methodological Contribution**: The approach underscores the effectiveness of combining advanced NLP techniques (like lemmatization and TF-IDF) with robust classification algorithms (like LinearSVC) to tackle sentiment analysis.

### Conclusion

This sentiment analysis project successfully developed a reliable model for classifying review sentiments using multiple datasets. Key techniques, including data cleaning and TF-IDF vectorization, significantly improved accuracy, especially with the handling of negation. The results highlight the importance of thorough preprocessing in NLP tasks and the potential for these models to provide valuable customer insights in real-time applications. Future work could explore deep learning models for further enhancements.
