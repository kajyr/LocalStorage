# LocalStorage
A simple PHP class to store key/value information on a text file.

Useful for rapid local prorotyping.

Not useful for production environments


##Basic usage:
```php
$config = new LocalStorage();

$config->set('bar, 'pippo');

$foo = $config->get('bar');

```