# 📧 Spam Filter using XGBoost

This project presents a robust spam filter built using the XGBoost classifier. The model is trained on an imbalanced dataset that is intelligently oversampled using NLP data augmentation techniques, yielding a high-performing classifier with **98.65% accuracy**.

## 🚀 Features

- Text preprocessing with TF-IDF Vectorizer
- Label encoding of target labels
- Oversampling of minority class (spam) using **NLPaug** with synonym replacement
- Classification using **XGBoost**
- Achieves **98.65% accuracy** on validation data

## 📊 Approach

### 1. Data Augmentation with NLPaug
To handle class imbalance, we augmented the spam class by generating semantically similar sentences using **NLPaug**'s synonym replacement technique. This helped to oversample the spam class while maintaining sentence context.

### 2. Feature Engineering
- **TF-IDF Vectorizer** was used to convert text data into numerical features.
- **LabelEncoder** was applied to transform text labels (`ham`, `spam`) into numerical format.

### 3. Classification with XGBoost
The transformed dataset was trained using **XGBoost**, a powerful and efficient gradient boosting framework known for its performance on structured data.

## 🧪 Performance

- **Accuracy:** 98.65%
- Evaluation metrics (confusion matrix, precision, recall, F1-score) confirm strong model performance with minimal false negatives.

## 📁 Project Structure

