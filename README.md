# SSL-enforcement
RewriteCond %{SERVER_PORT} 80 RewriteCond %{HTTP_HOST} ^(www\.)?domain\.com RewriteRule ^(.*)$ https://domain/$1 [R,L]
