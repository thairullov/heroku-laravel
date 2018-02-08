web: vendor/bin/heroku-php-nginx -C config/nginx.conf public/
worker: php artisan queue:listen --timeout=0
release: php artisan migrate -n