# Write the codes below!
FROM python:3.11-slim

LABEL author=ManuelGoesswein

EXPOSE 8000/tcp

WORKDIR /home/app
ADD hyper-app .

RUN pip install -r requirements.txt

ENTRYPOINT ["python3", "main.py"]
