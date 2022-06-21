# krakenD-example-configuration
Using docker to install and run KrakenD API Gateway

docker build -t nowo/krakend .

docker run -p 8000:8000 nowo/krakend run -d -c /etc/krakend/krakend.json
