# docker

手工运行命令

docker run -ti --rm --entrypoint="/bin/bash" daocloud.io/zuroc/gu321 -c "touch /var/log/supervisor/1"

docker exec -it gu321 bash
