# Web Scraping with Python (Completed)

A beginner's tutorial to scraping websites using Python's [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) library. This repository is the source code for the tutorial found here: 
https://www.djuices.com/web-scraping-with-python

## Installation

**Installation via `requirements.txt`**:

```shell
$ git clone https://github.com/hackersandslackers/beautifulsoup-tutorial.git
$ cd beautifulsoup-tutorial
$ python3 -m venv myenv
$ source myenv/bin/activate
$ pip3 install -r requirements.txt
$ python3 main.py
```

**Installation via [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/)**:

```shell
$ git clone https://github.com/hackersandslackers/beautifulsoup-tutorial.git
$ cd beautifulsoup-tutorial
$ pipenv shell
$ pipenv update
$ python3 main.py
```

**Installation via [Poetry](https://python-poetry.org/)**:

```shell
$ git clone https://github.com/hackersandslackers/beautifulsoup-tutorial.git
$ cd beautifulsoup-tutorial
$ poetry shell
$ poetry update
$ poetry run
```

## How to Use

This script will output metadata scraped from whichever URL is specified in **config.py**. Simply change the value of this variable to test the script against any URL of your choice.
