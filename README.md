# docker-kibana

Kibana as a Docker container based on Debian Jessie

## Kibana 3

As Kibana 3 is a strictly HTML + Javascript application exclusively, it doesn't
really need a server backend.

This container is just an nginx service serving the Kibana 3 static assets

### Configuration options

Mount your custom config.js into the container's `/kibana/config.js` path.

## Kibana 4

On the other hand, Kibana 4 is a Java server application.

### Configuration options

Mount your custom kibana.yml into the container's `/kibana/config/kibana.yml` path.
