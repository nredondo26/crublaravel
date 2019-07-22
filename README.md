# crublaravel
proyecto en el cual tienes los codigos fuentes de un crup en laravel

comandos:
composer create-project laravel/laravel=5.5 crudlaravel
php artisan make:migration create_libros_table
php artisan migrate
php artisan migrate:rollback
php artisan make:model Libro	
php artisan make:controller LibroController --resource

ruta:
Route::resource('libro', 'LibroController');

url con toda la informacion:
https://www.ecodeup.com/como-crear-un-crud-en-laravel-5-5-desde-cero/

