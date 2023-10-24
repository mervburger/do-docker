# do-docker
Collection of docker files for my digital ocean droplet

This droplet just runs docker, which is used to run the following services:

 - cloudflared - creates a Zero Trust tunnel with Cloudflare
 - traefik - proxy server
 - nginx - hosts an instance of nginx with the current data at mervburger/website
 - cloudlog - hosts an instance of [2m0sql/cloudlog](https://hub.docker.com/r/2m0sql/cloudlog)
