# Featured Attributes

It's a metapackage for the [source code repository](https://github.com/swissup/module-featured-attributes).

#### Installation

```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/featured-attributes --prefer-source
bin/magento module:enable Swissup_Core Swissup_FeaturedAttributes
bin/magento setup:upgrade
```
