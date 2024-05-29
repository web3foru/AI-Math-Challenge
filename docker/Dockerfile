FROM python:3.11-slim

WORKDIR /app

RUN pip install jupyterlab

COPY . .  

RUN pip install -r requirements.txt

CMD ["jupyter", "lab", "--ip=0.0.0.0", "--no-browser", "--allow-root"]


