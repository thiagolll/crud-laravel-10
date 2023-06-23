
### Step by step
Clone Repository
```sh
git clone https://github.com/thiagolll/crud-laravel-10.git
```

Create the File .env
```sh
cd example-project/
cp .env.example .env
```

Upload the project containers
```sh
docker-compose up -d
```


Access the container
```sh
docker-compose exec curso_x bash
```


Install project dependencies
```sh
composer install
```


Generate Laravel project key
```sh
php artisan key:generate
```

Use the postman collection to test endpoints
Download collection postman
https://mega.nz/file/F1YjwTJD#RwzA4eXAxVQ4xjDj9MLh3eJp2EACw2HeA7potZFS8Ck
