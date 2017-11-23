# Alpine-nginx

## Nginx
NGINX is open source software for web serving, reverse proxying, caching, load
balancing, media streaming, and more. It started out as a web server designed
for maximum performance and stability. In addition to its HTTP server
capabilities, NGINX can also function as a proxy server for email (IMAP, POP3,
and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.
[_source_](https://www.nginx.com/resources/glossary/nginx/)

## Dockerfile
* Alpine-nginx v3.0 
    * nginx v.1.12.2
    * alpine v.3.6

## How to use
clone images from docker hub
`docker pull mhfaris/alpine-nginx`

and then you can run images with this command
``sudo docker run -d -p 80:80 alpine-nginx:v3.0``


