FROM python:3.12-alpine

WORKDIR /app

COPY ./requirements.txt /app/requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

COPY . /app/

EXPOSE 5555

CMD ["python3", "/app/api/app/main.py"]
