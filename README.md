#DDShop
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://shushuyee.github.io/DDshop/index.html$1 [R,L]
