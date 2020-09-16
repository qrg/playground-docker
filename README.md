# Playground docker and docker-compose

環境変数に設定された文字列から docker image 名を組み立てて build するのを試す

```console
$ NODE_VERSION=12.18.3 docker-compose build 

$ docker-compose up --detach

$ docker-compose run app /bin/sh
WARNING: The NODE_VERSION variable is not set. Defaulting to a blank string.
Creating playground-docker_app_run ... done
/ # which node
/usr/local/bin/node
/ # node -v
v12.18.3
/ # exit
```

[LICENSE](./LICENSE)

