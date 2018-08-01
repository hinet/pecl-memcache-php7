# pecl-memcache-php7

memcached module for PHP
------------------------
This module requires zlib library, used for on-the-fly data (de)compression.
Also, you'll need memcached to use it =)

The memcached website is here:
    http://www.danga.com/memcached/

You will probably need libevent to install memcached:
You can download it here: http://www.monkey.org/~provos/libevent/

How to run tests:
1. sh tests/memcache.sh
2. TEST_PHP_EXECUTABLE=/usr/local/bin/php php -dextension=modules/memcache.so run-tests.php -d extension=modules/memcache.so

Maintainers:
Herman J. Radtke III	hradtke at php dot net

