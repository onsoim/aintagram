FROM python:3

LABEL maintainer="onsoim <onsoim@gmail.com>" 

ENV PYTHONUNBUFFERED=0

RUN apt-get update

RUN apt-get install -y \
	libpq-dev

WORKDIR /app

# ADD requirements.txt /app/

# RUN pip3 install -r requirements.txt