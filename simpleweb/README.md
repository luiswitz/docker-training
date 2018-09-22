# Simple Web

Simple project to cover the very basic of Docker

## Setup

```
docker build -t <your-image-name-here> .
```

In order to redirect the local network incoming traffic to the container we use the -p option

```
docker run -p 8080:8080 <your-image-name-here>
```
