FROM python:3.10

WORKDIR /app

COPY . /app

RUN pip install -e .

EXPOSE 8080

ENTRYPOINT [ "python", "/app/aiohttpdemo_chat/main.py" ]