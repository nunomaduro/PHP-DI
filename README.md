Dependency injection with annotations in PHP

## Introduction

The aim of PHP-DI is to make [Dependency Injection](http://en.wikipedia.org/wiki/Dependency_injection)
as simple as possible with PHP.

Unlike Zend\DI, Symfony Service Container or Pimple, PHP-DI:

* can be used by a monkey
* is not limited to Services (_anything_ can be injected)
* uses annotations for code-readability and ease of use


### Features

* Uses annotations for simplicity, readability and auto-completion in your IDE
    * `@Inject` annotation to inject a dependency
    * `@Value` annotation to inject a configuration value
* Optional lazy-loading of dependencies (`@Inject(lazy=true)`)
* Class aliases (interface-implementation mapping)
* Easy installation with [Composer](http://getcomposer.org/doc/00-intro.md) and easy integration with Zend Framework (see [Getting started](doc/getting-started))
* Non-intrusive: you can add PHP-DI into an existing project and use it *without impacting existing code*


### Installation

Read the [Getting started](doc/getting-started) guide.


### Documentation

Read the [documentation](doc/).


### Contribute

[![Build Status](https://secure.travis-ci.org/mnapoli/PHP-DI.png)](http://travis-ci.org/mnapoli/PHP-DI)

* Read the wiki: [Contribute](doc/contribute)
