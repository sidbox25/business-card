# business-card

- docker build -t myapp:v1.0 -f ./docker/App/dockerfile .
- docker run -e ServerName:172.1.0.0 -p 80:80 myapp:v1.0