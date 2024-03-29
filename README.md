# PHP Boilerplate

![PHP requirement](https://img.shields.io/packagist/php-v/webgarden/php-boilerplate?logo=php&style=for-the-badge "PHP requirement")
[![GitHub license](https://img.shields.io/github/license/thewebgarden/php-boilerplate?style=for-the-badge)](https://github.com/andrzejkupczyk/php-boilerplate/blob/main/LICENSE "License")
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/thewebgarden/php-boilerplate?sort=semver&style=for-the-badge)

A boilerplate for new composer-based PHP projects.

## Dependencies

This package aims to be as small and simple as possible. 
In fact, the only requirement is PHP 8.2, hence in order to add PHPUnit, PHP CS Fixer and [some other](phive.xml) frequently used development tools, 
it relies on [PHIVE](https://phar.io/).

## Getting Started

### Install PHIVE 

Make sure PHIVE is available on your system ([installation instructions](https://phar.io/#Install)):
```bash
$ phive --version
``` 

### Clone repository

#### Via [Composer Create-Project] (recommended)

```bash
$ php composer.phar create-project --prefer-source --remove-vcs webgarden/php-boilerplate new-project
```  

#### Using [GitHub Templates]

:link: https://github.com/thewebgarden/php-boilerplate/generate

[Composer Create-Project]: https://getcomposer.org/doc/03-cli.md#create-project
[GitHub Templates]: https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
