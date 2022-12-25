FROM datamechanics/spark:3.1-latest

ENV PYSPARK_MAJOR_PYTHON_VERSION=3

WORKDIR /opt/application

RUN pip3 install pyspark

COPY main.py .
COPY data.txt .