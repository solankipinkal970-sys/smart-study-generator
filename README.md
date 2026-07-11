# smart-study-generator
# 📚 Smart Study Generator

An AI-powered study platform that helps students generate summaries, quizzes, flashcards, concept maps, and personalized study plans from uploaded documents using IBM Watsonx Granite, ChromaDB, Flask, and RAG.

## 🚀 Features

* Upload PDFs, images, text, and audio files.
* Generate AI-powered summaries.
* Create flashcards automatically.
* Generate quizzes with instant feedback.
* Build concept maps.
* Create personalized study plans.
* Chat with uploaded documents using RAG.
* Track progress through an analytics dashboard.

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Flask

### AI & Database

* IBM Watsonx Granite
* ChromaDB
* IBM Langflow
* Sentence Transformers

### Libraries

* PyPDF2
* SpeechRecognition
* Pillow

## 📂 Project Structure

```text
smart-study-generator/
│
├── app.py
├── requirements.txt
├── README.md
│
├── utils/
├── database/
├── templates/
└── static/
    ├── css/
    └── js/
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/smart-study-generator.git
```

Go to the project folder:

```bash
cd smart-study-generator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Set up environment variables:

```env
WATSONX_API_KEY=your_api_key
WATSONX_PROJECT_ID=your_project_id
```

Run the application:

```bash
python app.py
```

Open in your browser:

```text
http://localhost:5000
```

## 🧠 How It Works

1. Upload study materials.
2. Extract text from files.
3. Generate embeddings.
4. Store data in ChromaDB.
5. Retrieve relevant content using RAG.
6. Generate intelligent responses using IBM Watsonx Granite.

## 🎯 Future Scope

* Mobile application support.
* Multi-language support.
* Voice-enabled AI assistant.
* Cloud integration.
* Advanced analytics.
* Collaborative learning features.

## 📜 License

This project is developed for educational purposes.
