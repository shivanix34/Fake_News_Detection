# Fake News Detection

## Abstract
This project uses AI and ML methods to create an effective system for detecting fake news. It focuses on linguistic pattern extraction, writing style analysis, and source credibility. A dataset of labeled news articles and metadata is curated, and preprocessing is performed to remove noise, handle missing values, and balance classes. Various ML algorithms such as logistic regression and random forest are explored. The system is designed for real-time applications and is accessible through a user-friendly website interface.

## Objective / Outcome of the Project
- Develop a system or algorithm that can accurately identify and distinguish between genuine news and fake news.
- Create a system that can detect fake news in real-time or near real-time.
- Develop a user-friendly interface or tool that allows users to easily access and utilize the fake news detection system.

## Design / Dataflow Diagram
1. **Loading the Dataset**: The dataset consists of labeled news articles classified as either "fake" (0) or "true" (1).
2. **Preprocessing**: The text data undergoes several preprocessing steps and is transformed into numerical features using the TF-IDF vectorization technique.
3. **Training**: Machine learning algorithms like Logistic Regression (LR) and Random Forest Classifier (RFC) are used for training.
4. **Evaluation**: The trained models are evaluated using testing data, and accuracy is computed using the score method.
5. **Prediction**: The system preprocesses input text, transforms it using pre-trained TF-IDF vectorization, and applies the trained LR and RFC models to make predictions.


## Language Used for Implementation with IDEs Used
- **Language**: Python
- **IDE**: Jupyter Notebook

### Libraries Used
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical computing.
- **Seaborn**: For statistical data visualization.
- **Matplotlib**: For creating plots, charts, and graphs.
- **Sklearn**: For machine learning tasks.
