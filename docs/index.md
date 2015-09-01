##About me

[dingjun](https://github.com/fangdingjun) at github.com

##Projects

###gdns

[gdns](https://github.com/fangdingjun/gdns/)
is a dns proxy server, much like dnsmasq, it can run on windows

Features

* support different domains use different upstream dns servers

* support use tcp or udp to contact to upstream dns server

* support blacklist to block the fake ip

###chnroutes
[chnroutes](https://github.com/fangdingjun/chnroues/)
is my fork of [chnroutes](https://github.com/fivesheep/chnroutes)

Features

* use netsh to save the time for import the route on windows, this will save time from 120s to 3s
* use `ip --batch` instead of `route` to save the time for import the route on linux

###http proxy
[http proxy](https://github.com/fangdingjun/myproxy)
is a generic http proxy handler write by go, it makes the server act as a standard proxy server and as a normal http server at the same time

If you use this handler as the https handler, your server support https and http proxy over tls (like https_port in squid)


