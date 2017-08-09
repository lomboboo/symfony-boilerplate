Symfony boilerplate
==========

* parameters.yml - configure ```mailer_user```, database's fields.
* composer install
* app/console cache:clear
* app/console assets:install
* app/console doctrine:migrations:diff
* app/console doctrine:migrations:migrate
* mkdir web/uploads
* mkdir web/uploads/media
* chmod -R 0777 web/uploads