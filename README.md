# Exercise in Channels: Chat App

This is a simple chat app showcasing the use of channels and web sockets in Django. In order to run this application, you will need [Docker](https://www.docker.com/), and [Pipenv](https://pipenv.pypa.io/en/latest/) installed.

## Installation

At the root of the project folder, run the following commands. This will run the virtual environment, and install all the necessary dependencies.

`pipenv shell`

`pipenv install`

## Running

Next, make sure your Docker server is running and input the following to start a Redis server:

`docker run -p 6379:6379 -d redis:5`
