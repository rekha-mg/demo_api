Laravel - sample - api app 

### To make first install

* `composer create-project --prefer-dist laravel/laravel demo_api`
* setup mysql password database in .env
* if database donest exist create one manullay 
* run `php artisan migrate`
* run `php artisan make:migration create_products_table`
* update `create_products_table` with schema changes you need.
* run `php artisan migrate`
* add Product, ProductController, and route
	![refer](https://www.itsolutionstuff.com/post/build-restful-api-in-laravel-58-exampleexample.html) - I have not enabled auth module from here.


### To clone from repo and run 

* Delete - vendor folder if exists 
* run `composer install`

### To start app
`php artisan serve`

### To test api

GET: http://localhost:8000/api/products
POST: http://localhost:8000/api/products
	* pass name & details in `form-data`