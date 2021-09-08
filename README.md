# nginx_main_proxy  
Проксирующий контейнер для хостинга.  
Для начла работы требуется создать network для docker.  
`docker network create nginx.docker`  
Создать папку conf.d в корне и переместить туда файл nginx.conf  
Создать папку certbot_extra_domains в корне и переместить туда файл domain.ru.  
Отредактировать конфиги в требуемых местах.  


