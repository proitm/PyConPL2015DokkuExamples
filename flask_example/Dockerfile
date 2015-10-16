FROM python:2.7

EXPOSE 5000

RUN mkdir /code
WORKDIR /code

ADD . /code
RUN pip install -r requirements.txt

CMD ["python", "blueprintexample.py"]
