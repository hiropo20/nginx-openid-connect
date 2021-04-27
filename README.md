# nginx-openid-connect for Access Token Test

Please see the original GitHub page for basic usage and configuration for OIDC of NGINX Plus
[nginxinc/nginx-openid-connect](https://github.com/nginxinc/nginx-openid-connect)

## Description
This repository is to add the feature to transfer Access Token to backend Server. This is lab code.

![OIDCaddAccessToken_BasicDiagram-20200427](https://user-images.githubusercontent.com/43058573/116189488-f80af280-a763-11eb-8742-5510d62d6ce8.jpg)

`Figure 1. High level components of an OpenID Connect environment`


![OIDCaddAccessToken_BasicFlow-20200427](https://user-images.githubusercontent.com/43058573/116189603-2983be00-a764-11eb-9fad-525d1e829f0e.jpg)

`Figure 2. Flow of an OpenID Connect`

## how to use 

`$ git clone <here>`

`$ cd nginx-openid-connect/`

`$ ./configure.sh <OpenID Connect Discovery URL>`

`$ cp <created configuration files> <NGINX configuration folder>`

And modify configuration files (mainly frontend.conf, openid_connect_configuration.conf) to fit your environment. 
