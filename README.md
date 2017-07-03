# Tinderify

[![Build Status](https://travis-ci.org/taseppa/tinderify.svg?branch=master)](https://travis-ci.org/taseppa/tinderify)

Tinder tool, supports autoswiping users, chatting and storing statistics.

## Installation
1. Install Python dependencies: `pip install flask pynder jsonpickle peewee`
2. Install frontend dependencies: `cd frontend && bower install`
3. [Get](https://gist.github.com/taseppa/66fc7239c66ef285ecb28b400b556938) your facebook access token and id. Run `cd backend && cp config.py.example config.py` and add your facebook auth info to config.py. 
4. Start with `python server.py` and open localhost:5000 in web browser.
