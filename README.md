# phpMyAdmin-all-languages
> Deployment ready version of phpmyadmin-all-languages.

[![GPL-2.0](http://img.shields.io/badge/license-GPL--2.0-green.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![Packagist](https://img.shields.io/packagist/v/wp-cloud/phpmyadmin.svg)](https://packagist.org/packages/wp-cloud/phpmyadmin)
[![GitHub tag](https://img.shields.io/github/tag/wp-cloud/phpmyadmin.svg)](https://github.com/wp-cloud/phpmyadmin/releases)

## WP-Cloud Version
> This version is a deployment-ready version of phpMyAdmin All-Languages.
> It contains all language files packaged in 'phpMyAdmin-*-all-languages.zip'.
>
> Following folders have been removed from the distribution package:
> - doc
> - examples
> - scripts
> - setup

## Composer Installation Sample

To install an application via Composer in a custom location you need a composer-installer.
You can use `oomphinc/composer-installers-extender` with a composer.json like this:

```json
{
    "name": "vendor/name",
    "description": "desc",
    "type": "project",
    "require": {
        "oomphinc/composer-installers-extender": "^1.1",
        "wp-cloud/phpmyadmin": "*"
    },
    "extra": {
        "installer-types": ["application"],
        "installer-paths": {
            "web/phpmyadmin/": ["wp-cloud/phpmyadmin"]
        }
    }
}
```

## License: _[GPL-2.0](http://www.gnu.org/licenses/gpl-2.0.html)_
Copyright © 1998 onwards -- the phpMyAdmin team

Details see: [phpMyAdmin Readme](README)
