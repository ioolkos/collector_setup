# collector_setup

This sets up an Opentelemetry Collector with OTLP receivers. It also sets up Jaeger and Zipkin as endpoints for the Collector.

There's no Collector agent. I use this to experiment with Opentelemetry in Erlang projects.

 `sudo docker-compose up -d`
 
 `sudo docker-compose logs -f`
 
 `sudo docker-compose down`

