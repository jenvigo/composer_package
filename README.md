# composer_package
A private composer package. 

##Usage
Add these lines to your composer.json

```
"require": {
"monolog/monolog": "2.2.0",
"jenvigo/composer_package": "dev-main"
},
"repositories": [
{
"type": "vcs",
"url": "https://github.com/jenvigo/composer_package"
}
],
"require-all": true, 
```
