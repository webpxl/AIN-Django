FROM python:3.12

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
COPY . /code
WORKDIR /code
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

CMD ["python", "championship/manage.py", "runserver", "0.0.0.0:7777"]