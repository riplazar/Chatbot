Cambiar en  Dockerfile 

FROM debian:stretch-slim AS chatscript-base 

A


FROM debian:buster AS chatscript-base



docker build -t chatscript-base .

docker run chatscript-base

docker-compose up -d --build

docker ps

docker exec -it BOT_TEMPLATE bash

BINARIES/LinuxChatScript64 client=localhost:1050


:reset (resetea el bot al incio)
