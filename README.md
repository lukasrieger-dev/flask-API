# flask-API

A simple API built with Python and flask.
It has three endpoints:
1.) / which displays a small documentation
2.) /sum to sum two numbers
3.) /mult to multiply two numbers

Example call: localhost:5000/sum?a=5&b=3

## Prerequisites
Python 3.8
flask
docker

## Docker commands
1.) docker build -t flask_api:latest
2.) docker run -d -p 5000:5000 --name=api flask_api

## Youtube Video Tutorial
https://www.youtube.com/watch?v=Poopo_K21Kw
