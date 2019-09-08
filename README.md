Symfony Demo Application
========================

The "Symfony Teste" is a reference application created to show how
to develop applications following the [Symfony Best Practices][1],
based on a basic "Symfony Demo Application".

Requirements
------------

  * PHP 7.1.3 or higher;
  * PDO-SQLite PHP extension enabled (php.ini -> extension=pdo_sqlite);
  * INTL PHP extension enabled (php.ini -> extension=intl)
  * and the [usual Symfony application requirements][2].

Installation
------------

Install the [Symfony client][4] binary and copy the aplication files [5]
in your HD or in your server document root path.

Usage
-----

There's no need to configure anything to run the application. If you have
installed the [Symfony client][4] binary, run this command to run the built-in
web server and access the application in your browser at <http://localhost:8000>:

```bash
$ cd project_path/
$ symfony server:start
```

If you don't have the Symfony client installed, run `php bin/console server:run`.
Alternatively, you can [configure a web server][3] like Nginx or Apache to run
the application.

Tests
-----

Execute this command to run tests:

```bash
$ cd project_path/
$ ./bin/phpunit
```

[1]: https://symfony.com/doc/current/best_practices/index.html
[2]: https://symfony.com/doc/current/reference/requirements.html
[3]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
[4]: https://symfony.com/download
[5]: https://github.com/crgrauppe/symteste
