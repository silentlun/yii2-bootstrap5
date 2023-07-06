<p align="center">
    <a href="http://getbootstrap.com/" target="_blank" rel="external">
        <img src="https://getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo.svg" height="80px">
    </a>
    <h1 align="center">Twitter Bootstrap 5 Extension for Yii 2</h1>
    <br>
</p>

This is the Twitter Bootstrap extension for [Yii framework 2.0](http://www.yiiframework.com). It encapsulates [Bootstrap 5](http://getbootstrap.com/) components
and plugins in terms of Yii widgets, and thus makes using Bootstrap components/plugins
in Yii applications extremely easy.


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer require --prefer-dist silentlun/yii2-bootstrap5
```

or add

```
"silentlun/yii2-bootstrap5": "*"
```

to the require section of your `composer.json` file.

Translations
----

The i18n configuration will be automatically added to your application configuration via bootstrapping process.

Usage
----

For example, the following
single line of code in a view file would render a Bootstrap Progress plugin:

```php
<?= yii\bootstrap5\Progress::widget(['percent' => 60, 'label' => 'test']) ?>
```
