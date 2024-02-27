# FROM python:3.6  
FROM python:3.6-slim 
#It is smaller in size, hence docker image size will reduce from 900+ MB to <150 MB

RUN pip install flask

COPY . /app/

EXPOSE 8283

WORKDIR /app

ENTRYPOINT ["python", "app.py"]

