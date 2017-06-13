Inflect
=======
[![Build Status](https://travis-ci.org/mmucklo/inflections.svg?branch=master)](https://travis-ci.org/mmucklo/inflections)


Inflect is an Inflector for PHP

Installation:
-------------
Add this line to your composer.json "require" section:

### composer.json
```json
    "require": {
       ...
       "mmucklo/inflect": "*"
```

Usage:
------

```php
use Inflect\Inflect;

echo Inflect::singularize('tests');
echo Inflect::pluralize('test');
```

Notes:
------

Many thanks to original author Sho Kuwamoto"
