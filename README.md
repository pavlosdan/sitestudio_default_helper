# Site Studio Default Helper
Allows site builders to select a default helper for a layout canvas field.

## Installation

To use this module, you must already have a Drupal site, and Acquia Site Studio.

Add the following to the `repositories` section of your project's composer.json:

```
"sitestudio_default_helper": {
    "type": "vcs",
    "url": "https://github.com/pavlosdan/sitestudio_default_helper.git"
}
```

or run:

```
composer config repositories.blt-site-studio vcs https://github.com/pavlosdan/sitestudio_default_helper.git
```

Require the module with Composer:

`composer require acquia/sitestudio_default_helper`

## Usage
- Navigate to an entity with a layout_canvas field.
- Go to the "Form Display" tab.
- Click the cog wheel on the layout canvas field.
- Select the default helper you want to load when the field first loads.
