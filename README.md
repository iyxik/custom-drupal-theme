# Custom Drupal Theme

A simple custom Drupal 11 theme created for assignment purposes.

## Overview

- Custom theme name: **Iyxik**
- Base theme: **Olivero** (default Drupal 10+ base)
- Includes a small Twig template override and CSS tweaks.
- Folder structure:

```
iyxik/
├── iyxik.info.yml
├── iyxik.libraries.yml
├── iyxik.theme
├── templates/
│   └── node.html.twig
└── css/
    └── style.css
```

## Features

- Custom CSS (background color, title styling)
- Twig override for node titles with a visible marker (🍦)
- Ready to install and enable on a Drupal 10/11 site

## Installation

1. Copy the `iyxik` folder into your Drupal site:

```
web/themes/custom/
```

2. Clear Drupal caches:

```bash
lando drush cr
```

3. Enable the theme:

**Appearance → Iyxik → Set as default**
