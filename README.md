# Tutorial symfony update to 3.3

Tutorial knp update symfony 3.x to 3.3

## Setup

```
composer install
```

**Setup the Database**

```
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
php bin/console doctrine:fixtures:load
```

**Start the built-in web server**

You can use Nginx or Apache, but the built-in web server works
great:

```
php bin/console server:run
```

Now check out the site at `http://localhost:8000`

Have fun!