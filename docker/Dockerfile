
FROM python:3.9.20-alpine


WORKDIR /app

COPY ./requirements.txt /app/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /app/requirements.txt

CMD ["fastapi", "dev", "main.py", "--host", "0.0.0.0", "--port", "80"]