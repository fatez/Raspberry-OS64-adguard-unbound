based on the idea of hat3ph/adguard-unbound 

have adapted the dockerfile to run on the raspberry OS64 with the following features : 

Base: arm64v8/alpine:latest \
Unbound installed from alpine: latest \
AdGuardHome from original repository: AdGuardHome_linux_arm64 v0.107.48 

Ports: 53/tcp 53/udp 67/udp 68/udp 80/tcp 443/tcp 853/tcp 853/udp 3000/tcp 5053/udp 5053/tcp 5443/tcp 5443/udp 853/tcp 784/udp 

An example of docker-compose.yaml is provided for you, just run "sudo docker-compose up -d" 

Credit: 

https://github.com/lolgast1987/adguard-unbound \
https://github.com/AdguardTeam/AdGuardHome 
