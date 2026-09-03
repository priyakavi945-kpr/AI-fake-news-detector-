📰 AI Fake News Detector

An AI-powered web application that uses Machine Learning and Natural Language Processing (NLP) to classify a news article as Likely Real or Likely Fake.

«⚠️ Disclaimer: This project provides a machine-learning prediction based on its training data. It is not a professional fact-checking system and should not be treated as proof that a news article is true or false.»

🚀 Features

- 📰 Enter or paste a news article
- 🤖 AI-based news classification
- 🟢 Likely Real / 🔴 Likely Fake prediction
- 📊 Model confidence score
- 🌐 Interactive Streamlit web interface
- 🧠 TF-IDF-based text feature extraction
- 📈 Logistic Regression machine-learning model
- 📂 Dataset-based model training

🛠️ Technologies Used

Technology| Purpose
Python| Main programming language
Pandas| Dataset processing
Scikit-learn| Machine Learning
TF-IDF| Text feature extraction
Logistic Regression| Classification
Streamlit| Web application
GitHub| Version control and project hosting

📁 Project Structure

AI-Fake-News-Detector/
│
├── app.py
├── train_model.py
├── fake_news_model.pkl
├── dataset.csv
├── requirements.txt
└── README.md

⚙️ How It Works

User enters news article
          ↓
      Text Input
          ↓
     TF-IDF Vectorizer
          ↓
   Machine Learning Model
          ↓
    Logistic Regression
          ↓
   Prediction + Confidence
          ↓
 Likely Real / Likely Fake

💻 Installation

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/AI-Fake-News-Detector.git

2. Open the project folder

cd AI-Fake-News-Detector

3. Install required packages

pip install -r requirements.txt

🧠 Train the Model

Run:

python train_model.py

This trains the machine-learning model using "dataset.csv" and creates:

fake_news_model.pkl

▶️ Run the Application

Start the Streamlit application:

streamlit run app.py

The application will open in your web browser.

📊 Dataset Format

The dataset should contain two columns:

text,label

Example:

text,label
"Government announces a new education program",real
"Scientists publish results from a new study",real
"Aliens secretly control every government",fake

For meaningful performance, use a sufficiently large and properly labeled dataset rather than the small example above.

🔮 Future Improvements

- 🔎 Add source/link verification
- 🌐 Integrate trusted fact-checking sources
- 📊 Add prediction history
- 📈 Add analytics dashboard
- 🧠 Compare multiple ML algorithms
- 🌍 Support multiple languages
- 📱 Improve mobile responsiveness
- ☁️ Deploy the application online
