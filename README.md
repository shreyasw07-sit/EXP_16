# EXP_16
NLP Techniques using Python (NLTK)
This repository contains fundamental Natural Language Processing (NLP) implementations using the NLTK (Natural Language Toolkit) library in Python. The project demonstrates core preprocessing steps required for any text-based machine learning or data science workflow.

👤 Student Information
Name: Shreyas Wani

PRN: 25070123131

Institute: Symbiosis Institute of Technology (SIT), Pune

🎯 Aim
To implement and understand various NLP techniques on text data, including tokenization, stop-word removal, stemming, lemmatization, and POS tagging.

🛠️ Technologies Used
Language: Python

Library: NLTK

Environment: Google Colab / Jupyter Notebook

📑 Key Features Implemented
1. Tokenization
Breaking down text into smaller units like words or sentences.

Word Tokenization: Splitting sentences into individual words.

Sentence Tokenization: Splitting paragraphs into individual sentences.

2. Text Cleaning
Stop-word Removal: Filtering out common words (e.g., "is", "the", "and") that do not carry significant semantic meaning for analysis.

3. Normalization
Stemming: Reducing words to their root or base form (e.g., "playing" becomes "play") using the PorterStemmer.

Lemmatization: Converting words to their meaningful dictionary form (lemma) using WordNetLemmatizer.

4. Linguistic Analysis
POS (Part-of-Speech) Tagging: Assigning grammatical categories (Noun, Verb, Adjective, etc.) to each word in a sentence.

Word Frequency Distribution: Calculating the occurrence of each word to identify dominant themes in the text.

🚀 How to Run
Clone the repository:

Bash
git clone https://github.com/your-username/nlp-techniques-python.git
Install the required dependencies:

Bash
pip install nltk
Run the notebook or script. Ensure you download the necessary NLTK corpora within your environment:

Python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
📊 Sample Output
Python
# POS Tagging Result
[('Python', 'NNP'), ('is', 'VBZ'), ('a', 'DT'), ('programming', 'JJ'), ('language'
