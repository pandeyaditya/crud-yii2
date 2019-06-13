INSTALLATION
------------

1) git clone 
2) create a database of your choice
3) create a table named customer

~~~
http://localhost/crud-yii2/web/
~~~


CONFIGURATION
-------------

### Database

Edit the file `config/db.php` with real data, for example:

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=yii2_demo',
    'username' => 'root',
    'password' => '123456',
    'charset' => 'utf8',
];
```

Import yii2_demo.sql

**NOTES:**
- Yii won't create the database for you, this has to be done manually before you can access it.
- Check and edit the other files in the `config/` directory to customize your application as required.
- Refer to the README in the `tests` directory for information specific to basic application tests.
