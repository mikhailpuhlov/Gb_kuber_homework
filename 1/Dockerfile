FROM python:latest

WORKDIR /app

COPY requirements.txt app.py ./

RUN pip install -r ./requirements.txt

EXPOSE 8080

CMD ["python", "./app.py"]


