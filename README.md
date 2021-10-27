# Fake-News-Detection-Using-Deep-Leearning
The main objective of this study was to develop a language independent detection method to detect fake news on social media in the first places and also on different platforms using long term memory networks - usually simply called "LSTM" - are a special type of RNN, then to assess the performance of our developed method. Such a method can optionally be integrated into a social network site to filter comments or tweets containing false information and also be integrated into any information exchange platforms.


# Overview:

Identifying public misinformation is a complicated and challenging task, and with the growth of the internet the spread of misinformation happens too quickly on a large scale.

To rectify this problem several people have come up with their solutions -  Most of them being crowdsourced like <https://www.altnews.in/> or BS Detector. They are web platforms dedicated to verifying and debunking the scourge of fake news in circulation.

The entire process involves the following:

1.  News article received
2.  A volunteer takes the article
3.  Does fact check for the entire article
4.  Determines if the article is Fake or not.

# The problem:

1.  Too many fake articles
2.  Each article takes too much time for fact checking
3.  Number of volunteers is very small
4.  Classifying fake news can be tough - https://miguelmalvarez.com/2017/03/23/how-can-machine-learning-and-ai-help-solving-the-fake-news-problem/

Read the above article to understand different types of fake news

# Our Solution:

Our machine learning model is made to help the fact checkers and not replace them. It reduces the time to to check articles by giving insights to the fact checker as to what level of scrutiny it should use for the particular article.


# Working:

## Dataset used :
https://github.com/rsx97/Dataset_fake_real

## Method used :
LSTM
https://colah.github.io/posts/2015-08-Understanding-LSTMs/

Final Result:

From the frontend app  you can enter any type of input : there is 7 methods of cleaning (numbers,urls,emojis.....)

## How it works :
Firstly you should create virtualenvironment for your flask project in yor desktop.

    install virtualenvironment : install virtualenvironment at your terminal or dos

    pip install virtualenv

    Clone the repository and access it with Windows PowerShell

    virtualenv venv : created virtualenvironment named "venv"

and activate your venv.
Now, you can start install flask.
-pip install Flask
-Run the Windows PowerShell
-Type in the command line : flask run

## DEMO Image:
<img src="https://github.com/rsx97/Fake-News-Detection-Using-Deep-Leearning/blob/main/static/images/Capture%20d%E2%80%99%C3%A9cran%20(25).png" width=800/>
