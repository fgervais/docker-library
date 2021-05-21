# Docker Images Library

## Debug

```
DOCKER_HOST=ssh://root@192.168.2.138 docker build -t debug -f Dockerfile.debug .
DOCKER_HOST=ssh://root@192.168.2.138 docker run -it --privileged --network host -v /root:/root -v /dev:/dev -h debug debug bash
```
