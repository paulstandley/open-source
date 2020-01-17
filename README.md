# __Paul Standley__

![profile](profile.png)

## OPEN-SOURSE

![open-soruse](open-soruse-logo.png)

Hello! This is an open organization in which everyone can do whatever they want! 💖

### Website open-sourse

---

## **Laravel 6**

### Bash **:-)**

```BASH

laravel new open-soruse

php artisan serve

composer require laravel/ui --dev

php artisan ui react --auth

npm install && npm run dev

composer require laravel/telescope --dev

php artisan telescope:install


```

After running __telescope:install__,
you should remove the __TelescopeServiceProvider__
service provider registration from your __app__ configuration file. Instead, manually register the service provider
in the __register__ method of your __AppServiceProvider__

```PHP

/**
 * Register any application services.
 *
 * @return void
 */
public function register()
{
    if ($this->app->isLocal()) {
        $this->app->register(TelescopeServiceProvider::class);
    }
}

```
