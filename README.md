# Seizure-Detection

A simple Flask API to receive EEG Datapoints, process the data, detect if a seizure has occurred, and return a response.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.

```bash
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
python app.py
```
The application will be started and it will start running on port - [3254](http://127.0.0.1:3254/)