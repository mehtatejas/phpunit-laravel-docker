# Docker image for testing Laravel applications with PHPUnit

Inspired by https://github.com/nielsvandoorn/docker-laravel-phpunit

## Running tests
Run the following command to run tests within the docker image:
```
docker run -v $(pwd):/app --rm nielsvdoorn/laravel-phpunit:latest ./vendor/bin/phpunit --configuration phpunit.xml tests
```

## Troubleshooting / Issues / Contributing
Feel free to open an issue in this repository. Contributions are also more than welcome.