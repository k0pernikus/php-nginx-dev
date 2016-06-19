# php7 dev stack

Provides a php7 dev stack using nginx and microimages.

# How to run

Install docker and docker-compose, and run:

```
docker-compose up
```
The hello world will be reachable at

```
http http://localhost:10080/
HTTP/1.1 200 OK
Connection: keep-alive
Content-Type: text/html; charset=UTF-8
Date: Sun, 19 Jun 2016 20:25:04 GMT
Server: nginx/1.10.1
Transfer-Encoding: chunked
X-Powered-By: PHP/7.0.7

Hello World
```
