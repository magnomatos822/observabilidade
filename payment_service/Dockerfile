FROM python:3.11

COPY requirements.txt /src/requirements.txt
RUN pip install -r /src/requirements.txt

WORKDIR /application
COPY . .

CMD ["python", "app.py"]
