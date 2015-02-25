# Genesis for Laravel MVC

Staying true to the Genesis projects, we bring you Genesis for Laravel MVC... a boilerplate structure of the Models, Views and Controllers for your [Laravel](http://laravel.com) apps.

Included in this repo are some MVC files that we found to be common to most of our Laravel applications. This ensures that you do not have to write the same standard models or views or controllers all over again.

_DRY for the win :)_

## Bonus

As an added bonus, we've included a few Migrations and Seeds for setting up your database schema.

## Versions

You are currently viewing the __Laravel 5.x__ MVC structure.

- For Laravel 5.* MVC, use the __master__ branch or __5.x__ branch.
- For Laravel 4.* MVC, switch to the __4.x__ branch.

## How to use

If you would like to use this MVC boilerplate in your app, simply follow these steps:

- Clone this repository into a folder on your computer: `git clone [clone_url] l5-mvc-boilerplate`
- Install Laravel 5.0 using [Composer](http://getcomposer.org) to your official project folder
- Copy and paste the folders: app, database and resources, from 'l5-mvc-boilerplate', into your Laravel application's project root
- If asked to overwrite, confirm overwrite (Don't worry, this should not break your app)
- Run database migrations and seeds: `php artisan migrate` then `php artisan db:seed`

Don't forget to update your application name with `php artisan app:name [YourAppName]`.

## License

[MIT License](http://choosealicense.org/mit)  
This license gives you freedom to use this code as you like.
