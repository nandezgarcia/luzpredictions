FROM python:3.10-alpine
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /codigo
COPY requirements.txt /codigo/
RUN pip install -r requirements.txt
COPY . /codigo/


