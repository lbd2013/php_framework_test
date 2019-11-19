### <font face="黑体">通过 Composer 创建项目</font>
```
alias php='docker exec php php' 
php /usr/bin/composer create-project --prefer-dist laravel/laravel /var/www/html/blog
chmod 777 -R /root/docker-lnmp/nginx/www/blog/
修改nginx配置，将root目录指向 
/root/docker-lnmp/nginx/www/blog/public
```
