# Setup

docker network create ssh_web

docker-compose -f docker/all.yml -p ssh_web up -d
