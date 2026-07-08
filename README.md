# DevelopersHub AI/ML Engineering Advanced Internship

# Task 1: News Topic Classifier Using BERT

---

## Project Overview

This project implements a **News Topic Classification** system using the **BERT (Bidirectional Encoder Representations from Transformers)** model. A pre-trained **bert-base-uncased** model is fine-tuned on the **AG News** dataset to classify news articles into four categories: **World, Sports, Business, and Science/Technology**.

The project demonstrates the complete Natural Language Processing (NLP) workflow, including data preprocessing, tokenization, model fine-tuning, evaluation, and deployment using **Gradio**.

---

## Problem Statement

Automatically categorizing news articles is an important Natural Language Processing (NLP) task that helps organize and retrieve information efficiently. This project leverages the power of transformer-based models to accurately classify news headlines into predefined categories.

---

## Objectives

- Load and explore the AG News dataset.
- Preprocess and tokenize text using the BERT tokenizer.
- Fine-tune the **bert-base-uncased** model.
- Evaluate model performance using Accuracy and F1-Score.
- Make predictions on unseen news articles.
- Deploy the trained model using Gradio.

---

## Dataset

- **Dataset:** AG News Dataset
- **Task Type:** Multi-class Text Classification
- **Classes:**
  - World
  - Sports
  - Business
  - Science/Technology

---

## Technologies Used

- Python
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Gradio

---

## Project Workflow

1. Load the AG News dataset.
2. Perform data preprocessing.
3. Tokenize text using the BERT tokenizer.
4. Fine-tune the BERT model.
5. Evaluate model performance.
6. Save the trained model.
7. Deploy using Gradio.

---

## Model

- **Model:** BERT (bert-base-uncased)
- **Framework:** Hugging Face Transformers
- **Task:** News Topic Classification

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

The fine-tuned BERT model successfully classifies news articles into four categories with strong classification performance. The project demonstrates the effectiveness of transformer-based models for text classification tasks.

---

## Project Structure

```text
developershub-task1-news-topic-classifier-bert/
│
├── bert_news_classifier.ipynb
├── README.md
├── requirements.txt
├── app.py
├── saved_model/
└── screenshots/
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/developershub-task1-news-topic-classifier-bert.git
```

### Navigate to the Project Folder

```bash
cd developershub-task1-news-topic-classifier-bert
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open:

```text
bert_news_classifier.ipynb
```

Run all cells sequentially using **Google Colab** or **Jupyter Notebook**.

To launch the Gradio application:

```bash
python app.py
```

---

## Key Learning Outcomes

- Fine-tuned a transformer-based BERT model for text classification.
- Applied tokenization using the Hugging Face tokenizer.
- Evaluated model performance using multiple classification metrics.
- Built an interactive Gradio application for real-time predictions.
- Gained practical experience in Natural Language Processing (NLP) workflows.

---

## Author

**Sara Sajid**  
BBA Student | Social Media Marketer | AI & Machine Learning Intern

---

## License

This project was developed for educational and internship purposes only.
