# pybot-gmail
python bot for gmail email crunching

this branch is develop and tested using python 2.7

follow the steps for gmail API: https://developers.google.com/gmail/api/quickstart/python

- select Other UI for creating credentials (Python)
- select user Data
- Download credentials i.e. Client ID	13456789-afewrewsdf.apps.googleusercontent.com
- rename the downloaded file to client_secret & put in the folder (Gitignore is added for this file)

Install library using command below
pip install --upgrade google-api-python-client
pip install --upgrade httplib2

you may run quickrun.py to test it.
if you encounter error, first look for the client_secret.json if existed.
