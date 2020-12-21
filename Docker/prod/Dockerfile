FROM python:3.6-slim-buster

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY src/ .

EXPOSE 5000
EXPOSE 8010

CMD ["python", "./app.py"]