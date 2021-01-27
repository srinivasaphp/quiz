## Laravel PHP Framework


## Installation

Recommended using [Homestead](http://laravel.com/docs/4.2/homestead) for development.

### 1. Clone the repo

    git clone https://github.com/manoj

### 2. Composer install

    cd LaravelQuiz
    composer install
    
### 3. Database 

Adjust the database information in app/config/database.php, then: 

    php artisan migrate

Seed the database if you want: 

    php artisan db:seed

### 4. Info(for seeded database)

* Admin Account: ['email' => 'admin@admin.com', 'password' => 'admin']
* Teacher Account: ['email' => 'teacher@teacher.com', 'password' => 'teacher']
* Student Account: ['email' => 'student@student.com', 'password' => 'student']

### 5.Debugging & error log
If you want to see what really happen:
* in  app/config/app.php  
	```
	'debug' => true,
	```
* in app/start/global.php
```   
//switch ($code) {
//       case 403:
//           return Response::view('error_pages.403', array(), 403);
//       case 500:
//           return Response::view('error_pages.500', array(), 500);
//       default:
//           return Response::view('error_pages.404', array(), 404);
//   }
```



## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

