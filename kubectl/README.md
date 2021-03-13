# Docker Image for Build
Imagem docker para construir container.

## Build

Criar imagem
```sh
docker build -t yurih567/docker:19.03-kubectl kubectl
```

Roda o shell na imagem criada
```sh
docker run -it --rm yurih567/docker:19.03-kubectl /bin/bash
```

## Release

Envia imagem para o hub.docker
```sh
docker push yurih567/docker:19.03-kubectl
```
