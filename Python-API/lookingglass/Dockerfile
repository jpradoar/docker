FROM alpine:3.13.1
COPY . /app
WORKDIR /app
RUN apk add python3 tcptraceroute iputils nmap py3-pip bind-tools && pip3 install flask
EXPOSE 8089
CMD python3 ./api.py
