# PHPUnit Skeleton Generator

THIS IS NOT YET A WORKING PROJECT.

`phpunit-skelgen` is a tool that can generate skeleton test classes from production code classes and vice versa.

## Installation

### Composer

Simply add a dependency on `rhavin/phpunit-skelgen` to your project's `composer.json` file if you use [Composer](http://getcomposer.org/) to manage the dependencies of your project. Here is a minimal example of a `composer.json` file that just defines a development-time dependency on phpunit/phpunit-skeleton-generator:

    "require-dev": {
        "phpunit/phpunit": "^11",
        "rhavin/phpunit-skelgen": "dev-master"
    },
    "repositories": [
        {
            "type": "vcs",
            "url":  "git@github.com:rhavin/phpunit-skelgen.git"
        }
    ]

For a system-wide installation via Composer, you can run:

    composer global require "rhavin/phpunit-skelgen=dev-master"

Make sure you have `~/.composer/vendor/bin/` in your path.

