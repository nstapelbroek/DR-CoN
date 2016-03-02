#DR CoN: Scalable Architecture using Docker, Registrator, Consul, Consul Template and Nginx

Build with:

```
docker build -t drcon .;
```

Run with:

```
docker run -it -e "CONSUL=10.200.2.1:8500" -e "SERVICE=hello-world" -p 80:80 nstapelbroek/blog-sd-nginx
```

`CONSUL` is the location of your Consul service, `SERVICE` is the query sent to consul which will be distributed across.

# Read more [here](http://www.maori.geek.nz/post/scalable_architecture_dr_con_docker_registrator_consul_nginx)
