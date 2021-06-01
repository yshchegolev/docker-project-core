FROM python:3.9
RUN git clone https://github.com/yshchegolev/python-weather.git ./app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python","./weather.py"]

