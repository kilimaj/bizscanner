# bizscanner

A machine learning project for scanning documents

Project structure

- Computer vision (OpenCV Tesseract OCR)

  - Scanning document
  - Identify location of text
  - Extract text from image

- Natural Language Processing (pandas spacy RegEx)
  - Extract entities from text
  - Cleaning and parsing

## installation Cheat Sheet

### How the project was created

- CD into watu folder and run the below cmd in the folder
- This first command to install virtualenv package for creating virtual environments

```
python -m venv env
```

- then this will create a virtual environment named watuenv

```
virtualenv named env
```

- to activate the environment

```
source env/bin/activate
```

```
pip list
```

- Installing all other packages

```
pip install -r requirements.txt
```

### Installing pytesaract

- Installing tesaract ocr first using brew

```
brew install tesseract
```

```
pip install pytesseract
```

### Installing spacy

- use the following link [https://spacy.io/usage]
