# CouchDB official dockerhub image with cors enabled

This image is automatically rebuild and available on dockerhub: https://hub.docker.com/r/trivago/couchdb-cors/

Image name: ``trivago/couchdb-cors:latest``

Configuration applied:

```ini
[httpd]
enable_cors = true

[cors]
origins = *
credentials = true
methods = GET, PUT, POST, HEAD, DELETE
headers = accept, authorization, content-type, origin, referer, x-csrf-token
```
