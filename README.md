# symfony-5-boilerplate
Boilerplate for a Symfony 5 application with basic dependencies installed

Controllers:
  * HomeController for a homepage => #[Route('/', name: 'app_home')]
    that returns a JSON message:
      {
        "message": "Welcome to your new Symfony 5 application!"
      }

Dependencies Installed:

  * maker-bundle
  * doctrine-annotations
  * orm
  * cors
  * security


Database Config:

  * DATABASE_URL="mysql://root@127.0.0.1:3306/symfony-5-boilerplate?serverVersion=mariadb-10.4.11&charset=utf8mb4"
