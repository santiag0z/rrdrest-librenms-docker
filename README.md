# RRDReST to LibreNMS
Docker file to run [RRDReST](https://github.com/tbotnz/RRDReST) (simple microservice to convert your RRDs into web services)

Container: [michaelwadman/rrdrest](https://hub.docker.com/r/michaelwadman/rrdrest)

> [!NOTE]  
>These instructions assume you are the **root** user.  
> If you are not, prepend `sudo` to the shell commands or temporarily become a user with root privileges with `sudo -s` or `sudo -i`.

## Download
```
cd /opt
git clone https://github.com/santiag0z/RRDReST-LibreNMS.git && cd RRDReST-LibreNMS
```

## Docker-compose up
```
docker-compose up -d
```