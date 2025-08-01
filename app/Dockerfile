# Dockerfile（放在 flask-devops-app/app 目录里）
FROM python:3.10-slim

WORKDIR /app

COPY . .

RUN pip install flask

CMD ["python", "app.py"]

