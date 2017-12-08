FROM resin/raspberrypi3-python:3.5.4-slim
WORKDIR /usr/src/app
COPY requirements.txt .
RUN pip install -r requirements.txt 

COPY . .
CMD python app.py
