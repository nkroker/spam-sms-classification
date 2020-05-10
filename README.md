# spamClassify

> **spamClassify** is the spam sms classification program written in python   
  - It uses Machine Learning to classify the text sms into 2 classification categories
    - spam
    - ham

### Actual Modeling
  - After testing multiple models finaly using **OneVsRestClassifier with TfidfVectorizer**
  - There is a test score added csv added for multiple models.

### Steps to install and play!
  - Clone repository
  - Make sure you have `Anaconda navigator installed`
  - Just run `conda create --name spamClassify --file ./requirements.txt`
  - Then `conda activate spamClassify`
  - For running flask api run `python SMS-classification-Model-API.py`
  - For tweeks and exploration run 'jupyter notebook'
  - Have fun! :sunglasses: :metal: :thumbsup:
