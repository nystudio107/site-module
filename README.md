# site-module for Craft CMS 3.x

An example module for Craft CMS 3 that lets you enhance your websites with a custom site module.

## Requirements

This module requires Craft CMS 3.0.0-RC3 or later.

## Installation

To install the plugin, follow these instructions.

1. Copy the `modules` folder into your project root directory

2. Either copy the `app.php` into your `config/` directory, or copy & paste the `*` settings in the `app.php` into your project's `app.php` file

3. Make sure you have the following in your project's `composer.json`:
```
  "autoload": {
    "psr-4": {
      "modules\\sitemodule\\": "modules/sitemodule/src/"
    }
  },
```

4. If you didn't have the above `autoload` settings in your `composer.json` you'll also need to do the following command from your project root:
```
composer dump-autoload
```

## site-module Overview

Read the [Enhancing a Craft CMS 3 Website with a Custom Module](https://nystudio107.com/blog/enhancing-a-craft-cms-3-website-with-a-custom-module) article for details.

## site-module Roadmap

Some things to do, and ideas for potential features:

* Initial release

Brought to you by [nystudio107](https://nystudio107.com/)
