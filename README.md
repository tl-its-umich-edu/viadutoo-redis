viadutoo-redis
==============

An add-on for [Viadutoo](//github.com/tl-its-umich-edu/viadutoo) to enable queueing messages in Redis

## About (for now)
A placeholder package for loading a specific revision of the [PHP Resque](//github.com/chrisboulton/php-resque) package 
for another project using Viadutoo.

## About (coming soon)
This will be an add-on package for Viadutoo to support storing messages in a Redis queue managed by PHP Resque.  Since 
not all Viadutoo users will need this Redis-based feature, it would be nice if PHP Resque could be an optional dependency 
of Viadutoo. However, [Composer](//github.com/composer/composer) doesn't have the ability to easily let package users 
specify whether an optional dependency should be installed.  Therefore, when this feature is needed, it and Viadutoo can 
be loaded by either:

* Requiring Viadutoo-Redis only, which will require the base Viadutoo package and PHP Resque.
* Requiring both Viadutoo and Viadutoo-Redis.  (Probably not a common usage, but it would work.  It may be
  useful for installing specific versions of Viadutoo and Viadutoo-Redis.)
