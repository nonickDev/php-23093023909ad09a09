# Start project

## run docker containers

```bash
git clone path_to_repository
cd project_namedocker-compose up -d --build
```

## init project

```bash
docker-compose exec php-clening sh
composer install
chown -R 1000:1000 .
chmod -R 777 storage
php ./artisan storage:link
php ./artisan migrate
php ./artisan db:seed
exit
```

```bash
npm install
npm run prod
```

## web

open in browser http://localhost:8080
