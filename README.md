# Flatpickr Contao component
A shim repositoy for [Flatpickr](https://github.com/flatpickr/flatpickr) as [Contao Component](https://github.com/contao-components/installer).

Branch 1.2 based on Flatpickr 4.3.

## Install

```
composer require heimrichhannot-contao-components/flatpickr
```


## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```php
$GLOBALS['TL_JAVASCRIPT']['flatpickr'] = 'assets/flatpickr/dist/flatpickr.min.js|static';
$GLOBALS['TL_USER_CSS']['flatpickr'] = 'assets/flatpickr/dist/flatpickr.min.css|static';
// Optional: Localization
$GLOBALS['TL_JAVASCRIPT']['flatpickr'] = 'assets/flatpickr/dist/l10n/de.js|static';
```

### Contao 3

```php
$GLOBALS['TL_JAVASCRIPT']['flatpickr'] = 'assets/components/flatpickr/dist/flatpickr.min.js|static';
$GLOBALS['TL_USER_CSS']['flatpickr'] = 'assets/components/flatpickr/dist/flatpickr.min.css|static';
// Optional: Localization
$GLOBALS['TL_JAVASCRIPT']['flatpickr'] = 'assets/components/flatpickr/dist/l10n/de.js|static';
```

