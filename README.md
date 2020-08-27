# Information / Информация

Интеграция информационных блоков в статью.

## Install / Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_InfoBox`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```php
wfLoadExtension( 'MW_EXT_InfoBox' );
```

## Syntax / Синтаксис

```html
{{#infobox: type = Website
| image =
| title = {{BASEPAGENAME}}
| type =
| url =
| owner =
| creator =
| language =
}}
```

## Donations / Пожертвования

- [Donation Form](https://donation-form.github.io/)
