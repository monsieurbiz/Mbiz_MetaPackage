# Mbiz_MetaPackage

This is a metapackage. It installs some modules which are required
in every new Magento 1 project.


## Usage

First you need to require some repositories:

```
composer config repositories.firegento composer https://packages.firegento.com
composer config repositories.monsieurbiz composer https://packages.monsieurbiz.com
```

Then you can require the meta package:

```
composer require monsieurbiz/mbiz_metapackage "*@dev"
```
