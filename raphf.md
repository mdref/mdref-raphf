# pecl/raphf

## About:

The "Resource and Persistent Handle Factory" extension provides facilities to manage those in a convenient manner.

## Installation:

This extension is hosted at [PECL](http://pecl.php.net) and can be installed with [PEAR](http://pear.php.net)'s pecl command:

    # pecl install raphf

> ***NOTE:***  
  Please note, that v1.x of ext-raphf works for PHP-5 and v2.x/master works for PHP-7 only.

### PHARext

Watch out for [PECL replicates](https://replicator.pharext.org?raphf)
and pharext packages attached to [releases](https://github.com/m6w6/ext-raphf/releases).

### Checkout

	git clone github.com:m6w6/ext-raphf
	cd ext-raphf
	/path/to/phpize
	./configure --with-php-config=/path/to/php-config
	make
	sudo make install

## INI Directives:

* raphf.persistent_handle.limit = -1  
  The per process/thread persistent handle limit.

## Internals:

> ***NOTE:***  
  This extension mostly only provides infrastructure for other extensions.
  See the API docs here:
  [v1.1.x](https://m6w6.github.io/ext-raphf/v1.1.x),
  [master](https://m6w6.github.io/ext-raphf/master).
