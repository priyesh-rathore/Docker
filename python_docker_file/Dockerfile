FROM python:3.9.13

RUN mkdir -p /code

WORKDIR /code

COPY ./requirements.txt /code/requirements.txt

RUN pip install -r /code/requirements.txt

COPY ./app /code/app

CMD ["python", "app/main.py"]
