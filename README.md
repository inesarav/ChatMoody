# ChatMoody
This is a mental health ChatBot, built for a final course project.

## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ git clone https://github.com/inesarav/ChatMoody
$ cd ChatMoody
$ python3 -m venv venv
$ . venv/bin/activate
```
Install dependencies
```
$ (venv) pip3 install Flask torch torchvision nltk
$ (venv) pip3 install flask-cors
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Run
```
$ (venv) python train.py
```
This will dump data.pth file. 
Run the following command to test it in the console.
```
$ (venv) python chat.py
```

Now for deployment follow my tutorial to implement `app.py` and `app.js`.
