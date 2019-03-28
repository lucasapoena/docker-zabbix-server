![Zabbix](https://assets.zabbix.com/img/logo/zabbix_logo_500x131.png)

# Zabbix Server Docker

### Nginx + Zabbix 4.0.5 + Mysql 5.7

### Requirements

**MacOS:**

Install [Docker](https://docs.docker.com/docker-for-mac/install/) and [Docker-compose](https://docs.docker.com/compose/install/#install-compose)

**Windows:**

Install [Docker](https://docs.docker.com/docker-for-windows/install/) and [Docker-compose](https://docs.docker.com/compose/install/#install-compose)

**Linux:**

Install [Docker](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/) and [Docker-compose](https://docs.docker.com/compose/install/#install-compose).

### How to use

Clone the project to your local repository:

```
git clone https://github.com/lucasapoena/zabbix-server-docker
```

Initialize your containers:

```
cd zabbix-server-docker
./start
```

### Panels

Enjoy your new panels!

**Zabbix Web:** http://localhost:8080

### Images used
[zabbix/zabbix-server-mysql:ubuntu-4.0.5](https://hub.docker.com/r/zabbix/zabbix-server-mysql)

[zabbix/zabbix-web-nginx-mysql](https://hub.docker.com/r/zabbix/zabbix-web-nginx-mysql)

### Features commands

| Commands  | Description  | Options & Examples |
|---|---|---|
| `./start`  | Initializes its containers  | |
| `./stop`  | Stop your project containers  | |
| `./kill`  | Stops containers and removes containers, networks, volumes, and images created to the specific project  | |

### License

MIT © 2019 [Lucas Apoena](https://github.com/lucasapoena/) and [contributors](https://github.com/lucasapoena/zabbix-server-docker/graphs/contributors).
