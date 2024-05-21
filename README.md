docker login --username nirmesh44 --password <token> ghcr.io
echo <token> | docker login ghcr.io -u nirmesh44 --password-stdin
 docker build . -t ghcr.io/nirmesh44/hello-nirmesh-ghcr:latest
 docker push ghcr.io/nirmesh44/hello-nirmesh-ghcr:latest