FROM python:2.7.17-alpine
ARG VERSION="beta"

ENV VERSION=${VERSION}
COPY app.py /

ENTRYPOINT ["python", "/app.py"]
