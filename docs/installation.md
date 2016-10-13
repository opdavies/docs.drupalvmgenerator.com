## Via Composer (recommended)

The recommended way to install the Drupal VM Generator is to require it globally with [Composer][0].

```bash
$ composer global require opdavies/drupal-vm-generator
```

When finished, you can test this by running `php ~/.composer/vendor/bin/drupalvm`.

Ensure that the `$HOME/.composer/vendor/bin` directory (or the equivalent directory for your OS) is in your `$PATH` so that the `drupalvm` executable can be located by your system.

## Via GitHub

For development purposes, you can also clone the project directly from [GitHub][1]:

```bash
git clone https://github.com/opdavies/drupal-vm-generator.git
```

When it is finished, you will also need to run `composer install` to download all of the dependencies.

Alternatively, you can perform both of these actions together using the `composer create-project` command:

```bash
composer create-project --prefer-source --dev opdavies/drupal-vm-generator:@dev
```

[0]: https://getcomposer.org
[1]: https://github.com/opdavies/drupal-vm-generator
