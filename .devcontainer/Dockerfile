FROM mcr.microsoft.com/devcontainers/python:0-3.8

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt && \
    rm -rf /root/.cache/pip && \
    rm requirements.txt