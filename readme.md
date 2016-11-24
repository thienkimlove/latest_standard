# Laravel PHP Framework

To set up

1. `cp .env.example .env`

2. Modify Database section and Google Authenticate section.

3. `php artisan composer install`.

4. `php artisan key:generate`

5. `chmod -R 777 public/files && chmod -R 777 storage && chmod -R bootstrap`

6. The example code located in `example` directory and will be update usually.

7.  Data share across views should be located in `app\Providers\AppServiceProvider.php`.

8. `config/site.php` is the main config for modules.

9. `app/Site.php` is main place for call static function across project.

10. 