Email Spam Classifier
This project focuses on building a high-precision Email Spam Classifier using Natural Language Processing (NLP) and Machine Learning ensemble techniques. The model is designed to distinguish between "Spam" and "Ham" (legitimate) emails with a high level of accuracy and precision.

🚀 Project Overview
The project follows a rigorous end-to-end data science pipeline:

Data Cleaning: Dropping unnecessary columns, handling duplicates, and encoding target labels.

EDA (Exploratory Data Analysis): Visualizing data distribution and generating descriptive statistics for character and word counts.

Data Preprocessing:

Lowercasing and Tokenization.

Removal of special characters, stop words, and punctuation.

Stemming using PorterStemmer.

Model Building: Implementing and comparing multiple algorithms including Naive Bayes, Random Forest, and SVC.

Ensemble Methods: Using Voting Classifiers and Stacking Classifiers to improve overall performance.

📊 Performance Metrics
The final model achieves impressive results, specifically optimized for high precision to avoid misclassifying important emails as spam:

Accuracy: ~97.87%

Precision: ~93.28%

🛠️ Requirements & Dependencies
To run this project, ensure you have the following installed:

numpy

pandas

nltk

scikit-learn

matplotlib / seaborn

pickle (for model deployment)

Install dependencies:

Bash
pip install numpy pandas nltk scikit-learn matplotlib seaborn
📖 Deployment Ready
The notebook concludes by exporting the trained model and the TF-IDF vectorizer using pickle. These files (model.pkl and vectorizer.pkl) can be directly integrated into a web application (e.g., Streamlit) for real-time email classification.

📈 Key Visualizations
Pie Chart: Distribution of spam vs. ham.

Heatmaps: Correlation matrices of text features.

Word Clouds: Identifying the most frequent terms used in spam and ham messages.

Author
Sahil First-year student at Elphinstone College, Mumbai IBM Certified in Python for Data Science & AI

Note: This project demonstrates advanced NLP preprocessing and the power of ensemble learning in classification tasks.
