# syntax=docker/dockerfile:1
FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /app-server
COPY requirements.txt /app-server/
RUN pip install -r requirements.txt
COPY . /app-server/
