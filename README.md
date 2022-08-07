[![Latest Stable Version](http://poser.pugx.org/nguyenanhung/template-backend-package/v)](https://packagist.org/packages/template-backend-package) [![Total Downloads](http://poser.pugx.org/nguyenanhung/template-backend-package/downloads)](https://packagist.org/packages/nguyenanhung/template-backend-package) [![Latest Unstable Version](http://poser.pugx.org/nguyenanhung/template-backend-package/v/unstable)](https://packagist.org/packages/nguyenanhung/template-backend-package) [![License](http://poser.pugx.org/nguyenanhung/template-backend-package/license)](https://packagist.org/packages/nguyenanhung/template-backend-package) [![PHP Version Require](http://poser.pugx.org/nguyenanhung/template-backend-package/require/php)](https://packagist.org/packages/nguyenanhung/template-backend-package)

# Template start Backend API Package

Template for repository Backend API - Basic, Simple and Lightweight

## Use this Template

First, you can `Use this template` for new project: [Use this template](https://github.com/nguyenanhung/template-backend-package/generate)

Second, clone your project to your to path in your machine

Finally, your edit file `composer.json` in root folder of project

```json
{
    "type": "library",
    "name": "nguyenanhung/template-backend-package",
    "description": "Structure Repository Template for Backend API Service Package",
    "keywords": [
        "backend",
        "helper",
        "library",
        "php"
    ],
    "homepage": "https://github.com/nguyenanhung/template-backend-package",
    "license": "MIT",
    "minimum-stability": "stable",
    "authors": [
        {
            "name": "Nguyen An Hung",
            "email": "dev@nguyenanhung.com",
            "homepage": "https://nguyenanhung.com",
            "role": "Developer"
        }
    ],
    "require": {
        "php": ">=7.1.3",
        "ext-curl": "*",
        "ext-json": "*",
        "ext-mbstring": "*",
        "nguyenanhung/my-debug": "^3.0 || ^2.0",
        "nguyenanhung/my-cache": "^3.0 || ^2.0",
        "nguyenanhung/requests": "^3.0 || ^2.0",
        "nguyenanhung/database": "^3.0 || ^2.0",
        "nguyenanhung/monitor": "^3.0 || ^2.0",
        "nguyenanhung/helpers": "^3.0 || ^2.0",
        "nguyenanhung/security": "^3.0 || ^2.0",
        "nguyenanhung/validation": "^1.0",
        "lcobucci/jwt": "^4.1 || ^4.0 || ^3.4.6"
    },
    "require-dev": {
        "nguyenanhung/seo": "^3.0 || ^2.0",
        "nguyenanhung/image": "^3.0 || ^2.0",
        "nguyenanhung/upload": "^2.0",
        "nguyenanhung/mailer-sdk": "^3.0",
        "tramtro/make-some-noise": "^1.0"
    },
    "autoload": {
        "psr-4": {
            "nguyenanhung\\Backend\\Your_Project\\": "src/"
        },
        "files": [
            "helpers/helpers.php"
        ]
    }
}
```

Replace name space `REPLACE_FOR_YOUR` to Project Backend space, example: `Google`. After change namespace, project namespace same `"nguyenanhung\\Backend\\Google\\": "src/"`

Finished, your can writing new awesome helper and library now time.

## Contact & Support

If any question & request, please contact following information

| Name        | Email                | Skype            | Facebook      |
|-------------|----------------------|------------------|---------------|
| Hung Nguyen | dev@nguyenanhung.com | nguyenanhung5891 | @nguyenanhung |

From Vietnam with Love <3