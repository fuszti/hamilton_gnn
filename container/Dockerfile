FROM pytorch/pytorch:1.11.0-cuda11.3-cudnn8-runtime

RUN DEBIAN_FRONTEND=noninteractive apt-get update && apt-get install -y \
    git vim

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt