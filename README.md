# mysql_docker_dev

MySQLとPHPをDocker上で動かすためのサンプル

## Note

MySQL と PHP を動作させるための必要最低限の構成なので、アプリケーションを作成する際にそのまま使用することはお勧めしません。

## Build Up

```Shell
# Start the docker
$ docker compose up -d --build
# Stop the docker
$ docker compose down
```

## Requirements

Docker がお手元のPCにインストール済みであることを確認してください
```Shell
$ docker --version
```

- [Install docker for mac](https://docs.docker.com/docker-for-mac/install
  )
- [Install docker for Windows](https://docs.docker.com/docker-for-windows/install
  )

## Access

- [Web](http://localhost:10080/)
- [phpMyAdmin](http://localhost:8080/)