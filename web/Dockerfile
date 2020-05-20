FROM jupyter/scipy-notebook:latest
WORKDIR /usr/src/app
COPY requirements.txt .
RUN pip install --no-cache-dir  -r requirements.txt
COPY . .
CMD ["runipy","modelserver.ipynb"]