Mandrill Prometheus Exporter
============================

[Mandrill](https://www.mandrill.com/) is a Transactional Email Service. If you are using it you might be 
interested in monitoring statistics they are offering via their [API](https://mandrillapp.com/api/docs/)

This tool helps you doing this when you are using [Prometheus](https://prometheus.io/) as monitoring system.
It is an exporter that runs as a standalone application and can be scraped by prometheus. 

Usage
------

It is recommended to use the exporter with Docker. 

```
docker run -p 9153:9153 -e "MANDRILL_API_KEY=<YOUR_API_KEY>" -d hypoport/mandrill-prometheus-exporter
``` 


