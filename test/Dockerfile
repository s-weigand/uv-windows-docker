# escape=`

ARG BASE_IMAGE
FROM ${BASE_IMAGE}

COPY test .

RUN uv run test.py
