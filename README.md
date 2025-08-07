EMAIL_CLASSIFICATION_MODEL
Spam Email Detector - Gradio App
--------------------------------

📌 Project Overview:
This project uses a Naive Bayes machine learning model trained on SMS data to classify messages as "Spam" or "Not Spam". It features a user-friendly interface built using Gradio with a light blue theme.

🛠 Technologies Used:
- Python
- Scikit-learn
- Pandas
- Joblib
- Gradio
- Regex (Text Cleaning)

🎯 Features:
- Input a message and get real-time spam detection.
- Displays prediction result with a confidence score.
- Clean, responsive interface using custom CSS in Gradio.

📂 Project Files:
- `app.py`           → Main Gradio app
- `spam_classifier_model.pkl` → Trained Naive Bayes model
- `tfidf_vectorizer.pkl`      → TF-IDF vectorizer used for training

▶ How to Run:
1. Make sure all `.pkl` files are in the same directory as `app.py`.
2. Install required libraries:
   pip install gradio scikit-learn pandas joblib
3. Run the app:
   python app.py
4. The Gradio UI will open in your browser.

👨‍💻 Author:
Muzammil – Machine Learning Intern

📅 Date:
August 2025
