# This package is abandoned and no longer maintained. 

---
# Media Library GCS URL Generator
A Laravel package to allow you to generate URLs for media managed by [spatie/laravel-medialibrary](https://github.com/spatie/laravel-medialibrary) when it is stored on a Google Cloud Storage filesystem (using [Superbalist/laravel-google-cloud-storage](https://github.com/Superbalist/laravel-google-cloud-storage)).

## Installation
Add the package to your Laravel project using composer:

```bash
$ composer require leewillis77/medialibrary-gcs-url-generator
```

## Configuration
Set the class as the `custom_url_generator_class` in `config/medialibrary.php`:

```php
'custom_url_generator_class' => 'Leewillis77\MedialibraryGcsUrlGenerator\MedialibraryGcsUrlGenerator',
```
