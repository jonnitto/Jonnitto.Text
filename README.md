Jonnitto.Text Package for Neos CMS
==================================

[![Latest Stable Version](https://poser.pugx.org/jonnitto/text/v/stable)](https://packagist.org/packages/jonnitto/text)
[![Total Downloads](https://poser.pugx.org/jonnitto/text/downloads)](https://packagist.org/packages/jonnitto/text)
[![License](https://poser.pugx.org/jonnitto/text/license)](https://packagist.org/packages/jonnitto/text)

With this package you add a text NodeType into [Neos CMS](https://www.neos.io).  
Contributions are very welcome!


If you want to get a fast overview, take a look at [Settings.yaml](Configuration/Settings.yaml) and [NodeTypes.Content.yaml](Configuration/NodeTypes.Content.yaml) in the [Configuration](Configuration) folder.

Installation
------------

Most of the time you have to make small adjustments to a package (e.g. configuration in `Settings.yaml`). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under `Packages/Sites/`. To install it correctly go to your theme package (e.g.`Packages/Sites/Foo.Bar`) and run following command:

```
composer require jonnitto/text --no-update
```

The `--no-update` command prevent the automatic update of the dependencies. After the package was added to your theme `composer.json`, go back to the root of the Neos installation and run `composer update`. Et voilà! Your desired package is now installed correctly.



License
-------

Licensed under MIT, see [LICENSE](LICENSE)
