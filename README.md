
# Sentiment Analysis Web App

Welcome to the Sentiment Analyser web app project! This repository contains the code for a Flask web application that performs sentiment analysis on user-provided text. Below is an overview of the project and instructions on how to use and run the application.
### INPUT
![Screenshot 2024-01-28 at 12 44 59 PM](https://github.com/ananyamanjunath/Sentiment-Analyser/assets/109954683/38e96b5f-a015-4dd7-8018-7c45dd66ab28)
### OUTPUT
![Screenshot 2024-01-28 at 12 45 51 PM](https://github.com/ananyamanjunath/Sentiment-Analyser/assets/109954683/b8bd102b-f17a-4636-bd41-e1a25f2b0259)

## Overview

The main file, `app.py`, is the Flask application that handles routes and sentiment analysis logic. The web app allows users to input text, analyzes the sentiment using the NLTK Sentiment Intensity Analyzer, and displays the result on a separate page. The project also includes HTML templates for the main and result pages, along with a CSS file for styling.

## Installation

To run the web app, make sure you have the following dependencies installed:

-   Flask
-   googletrans
-   nltk

You can install these dependencies using the following command:

```bash
pip install Flask googletrans nltk
```

## Usage

1.  Clone this repository:

```bash
git clone https://github.com/ananyamanjunath/Sentiment-Analyser.git
cd Sentiment-Analyser
```

2.  Run the Flask application:

```bash
python app.py
```

3.  Open your web browser and go to http://127.0.0.1:5000/ to access the Sentiment Analyser web app.
    
4.  Enter your text in the provided textarea, submit the form, and view the sentiment analysis result.
    

## Acknowledgments

This web app was developed using Flask, NLTK, and the Google Translate API for language detection and translation. Feel free to explore and modify the code based on your requirements.

Please note that the web app is currently set to run in debug mode. Ensure that it meets your security and deployment standards before deploying it in a production environment.
