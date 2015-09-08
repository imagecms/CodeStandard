# ImageCMS PHP CodeSniffer Coding Standard

## Installation

### Composer

This standard can be installed with the [Composer](https://getcomposer.org/) dependency manager.

1. [Install Composer](https://getcomposer.org/doc/00-intro.md)

2. Install the coding standard as a dependency of your project

        composer require --dev imagecms/coding-standard:>=1.0

3. Add the coding standard to the PHP_CodeSniffer install path

        application/third_party/bin/phpcs --config-set installed_paths application/third_party/imagecms/coding-standard

4. Check the installed coding standards for "ImageCMS"

        application/third_party/bin/phpcs -i

5. Done!

        application/third_party/bin/phpcs /path/to/code