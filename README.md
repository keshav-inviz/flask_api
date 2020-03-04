# flask_api
Flask application to save, update, delete and find data stored in [mongodb](https://docs.mongodb.com/) using api.

You can also use [postman](https://learning.postman.com/docs/postman/api-documentation/documenting-your-api/) to verify ur requests.
## Installation
```bash
sudo apt-get update

sudo apt-get -y install python3.3
```

## Requirement
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Flask and Pymongo
```bash
pip install flask

pip install pymongo
```
You can create a virtual environment and install the required packages with the following commands:
``` bash
$ virtualenv venv

$ . venv/bin/activate

(venv) $ pip install -r requirements.txt
```
## Running The Example
```bash
(venv) $ python3 add.py
```