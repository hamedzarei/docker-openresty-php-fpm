## PHP-fpm Openresty Dockerfile

based on: https://github.com/chenyongze/docker-openresty-php-fpm

added features:

*   php postgres connection module
*   luarock
*   lua libraries: json, hash, jwt, http request

#### build via
docker build -t op .

#### run and test via
docker run -p 8080:80 op

this will show php configurations page
