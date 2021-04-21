# CDV RIA Simple Customer App (SCM)

## Backend

Technologies:
- PHP 8.0.1
- Composer 2
- Symfony: 5.2.6
- Symfony CLI
- API Platform
- PostgreSQL 13 database

### Project instalation (localhost)



Determining PHP version for Symfony
```bash
echo 8.0 >> .php-version
```

Installing dependencies

```bash
composer install
```

Creating database
```bash
symfony console doctrine:migrations:migrate
```

Running project
```bash
symfony serve
```
