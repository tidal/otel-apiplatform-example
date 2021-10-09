API Platform application for development and testing of the opentelemtry-symfony-bundle.


The official API Platform documentation is available **[on the API Platform website](https://api-platform.com)**.

Running then API application against a local or remote development clone of **[open-telemetry/opentelemetry-php-contrib](https://github.com/open-telemetry/opentelemetry-php)**:

- cd api/
- cp composer.json composer-dev.json
- adjust the repository entry in composer-dev.json to point to your repo.
- Prepend any subsequent calls to composer with "COMPOSER=composer-dev.json". eg.: COMPOSER=composer-dev.json composer install


