# PHP-Youtube-class

## Usage:

### Print Youtube thumbnail <image> tag

```php
<?php echo Youtube::thumbnail([id or url], 'mq') ?>
```

### Get Youtube thumbnail url

```php
<?php echo Youtube::thumbnail_url([id or url], 'mq') ?>
```

### Print Youtube <embed> tag

```php
<?php echo Youtube::embed([id or url], [
  'width'=>'854',
  'height'=>'478',
]) ?>
```

### Get Youtube ID by video URL

```php
<?php echo Youtube::get_id([url string]) ?>
```
