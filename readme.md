## What is CodeIgniter

CodeIgniter is an Application Development Framework - a toolkit - for people
who build web sites using PHP. Its goal is to enable you to develop projects
much faster than you could if you were writing code from scratch, by providing
a rich set of libraries for commonly needed tasks, as well as a simple
interface and logical structure to access these libraries. CodeIgniter lets
you creatively focus on your project by minimizing the amount of code needed
for a given task.

## Dependency Management (Composer)

> Composer is a tool for dependency management in PHP

Installation

```shell
$ curl -sS https://getcomposer.org/installer | php
```
Create new file named `composer.json`

```json
{
	"description" : "Get Started",
	"name" : "simlegate/CI-get-started",
	"require": {
		"php": ">=5.4.24"
	},
	"require-dev": {
		
	}
}
```

Globally Config
```shell
$ mv composer.phar /usr/local/bin/composer
```
Then, just run composer in order to run `Composer` instead of `php composer.phar`.
