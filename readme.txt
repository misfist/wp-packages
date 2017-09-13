=== LittleSis Blog Project ===
Contributors: misfist
Requires at least: 4.7
Tested up to: 4.8.1
License: GPLv3

WordPress packages.

== Description ==
Starter package configuration for WordPress plugins and themes.

== Installation ==
The `composer.json` file contains the packages used by the site.

Run `composer install` (or `composer install --no-dev`) within the package directory in order to install for the first time.
Run `composer update` (or `composer update --no-dev`)  within the package directory in order to update the project.

Important: When installing or updating on a production environment, use the `--no-dev` flag so that packages used for development are not included.

Project structure

```
webroot
 \\_ wp-packages <-- contains composer.json - installs packages into `wordpress` directory
 \\_ wordpress <-- contains wordpress core and packages
```

== Changelog ==

0.0.1 - Initial
