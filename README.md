<!-- 
 
-->

<a href="https://sirthxalot.github.io/laravel-bulma/" target="_blank">
    <p align="center">
        <img alt="Logo STA-Laravel Bulma!"
             width="353.1px" height="100px"
             src="https://gitlab.com/sta-laravel/community/artwork/-/wikis/uploads/f2a2be6218169ca4d7e8bf35971ce2ec/logo_sta-laravel-bulma.svg" 
         />
    </p>
</a>

<h3 align="center"><i>RESPONSIVE WEB DESIGN GETS A WHOLE LOT FASTER!</i></h3>


<p align="center">
  <a href="https://travis-ci.org/Maatwebsite/Laravel-Excel">
    <img src="https://travis-ci.org/Maatwebsite/Laravel-Excel.svg?branch=3.1" alt="Build Status">
  </a>

  <a href="https://styleci.io/repos/14259390">
    <img src="https://styleci.io/repos/14259390/shield?style=flat" alt="StyleCI">
  </a>

   <a href="https://packagist.org/packages/maatwebsite/excel">
      <img src="https://poser.pugx.org/maatwebsite/excel/v/stable.png" alt="Latest Stable Version">
  </a>

  <a href="https://packagist.org/packages/maatwebsite/excel">
      <img src="https://poser.pugx.org/maatwebsite/excel/downloads.png" alt="Total Downloads">
  </a>

  <a href="https://packagist.org/packages/maatwebsite/excel">
    <img src="https://poser.pugx.org/maatwebsite/excel/license.png" alt="License">
  </a>
</p>

<p align="center">

**Content**             | **Website**
:---------------------- | :-----------------------------------------------------
**Source Code**         | https://github.com/sirthxalot/laravel-bulma
**API Documentation**   | https://sirthxalot.github.io/laravel-api
**Documentation**       | https://sirthxalot.github.io/laravel-bulma
**Personal Support**    | https://sirthxalot.github.io/laravel-bulma
**Issue Tracker**       | https://sirthxalot.github.io/laravel-bulma
**Code of Conduct**     | https://sirthxalot.github.io/laravel-bulma
**Contributing**        | https://sirthxalot.github.io/laravel-bulma
**Support Policy**      | https://sirthxalot.github.io/laravel-bulma
**Security Policy**     | https://sirthxalot.github.io/laravel-bulma
**Changelog**           | https://sirthxalot.github.io/laravel-bulma
**License**             | https://sirthxalot.github.io/laravel-bulma
 
</p>

Introduction
--------------------------------------------------------------------------------

The STA-Laravel Bulma is a family of responsive [front-end presets] 
(UI's) that make it easy to design beautiful responsive websites, apps 
and emails that are compatible with the [Laravel PHP framework][Laravel]. 
It is semantic, readable, flexible, and completely customizable. Start
building amazing content-focused websites based on the the [Bulma CSS 
framework][bulma] and the [Vue.js JavaScript framework][vue] optimized 
for common business use-cases.

Features
--------------------------------------------------------------------------------

### Latest Technologies

For users who can embrace the newest of technology, STA-Laravel Bulma 
comes with an optional Flexbox based grid and Ecmascript straight out 
of box. 

### Progressive Enhancement

Upload your responsive design web pages to get contextual feedback on 
any breakpoint or use one of tons pre-made building blocks to quickly extend
the behaviour. We are constantly adding new building blocks that help
people quickly prototyping.

### Building Blocks

We made some shiny new templates to kick off your next site or get some 
layout ideas. Pop these pre-made building blocks into your projects and 
save yourself time and resources.

### Localization Support

We focused on localization features to help designers around the world 
design great products faster. STA-Laravel Bulma supports right-to-left 
languages, handles the charset or do other stuff that needs to be done
in order to run your application worldwide. In fact STA-Laravel Bulma
is translated straight out of box. All texts has been translated into
german.

### Site Optimization

The websites are semantic correct, optimized for search engines (SEO) 
and build with performance in mind. We use all the technologies and 
concepts that help us to improve the experience or tracing. 

### Solution for Everything

We have tried to cover as many business cases as possible. If there is
no pre-made solution you probably will be able to use our components
to get success. These reusable building blocks can easy be customized
or enhanced for your needs.

Requirements
--------------------------------------------------------------------------------

### Composer

https://getcomposer.org

This package utilizes Composer to manage its [PHP dependencies]. 
So, before using STA-Laravel Bulma, make sure you have installed the 
**latest version of Composer** on your machine:

```bash
composer --version
```

Please use the [`composer self-update`] command frequently, in order 
to update Composer to its latest version.

### NPM or Yarn (optional)

Basically [NPM] and [Yarn] do the same like Composer does except that
their dependency focuses on [Node.js] or JavaScript dependencies. Both
can be used in order to manage the assets, e.g. stylesheets or JavaScripts 
in combination with [Laravel Mix]. 

All assets are already compiled and are ready to use in production. So
**you don't need to use NPM or Yarn**. However if you would like to recompile
or customize the assets you must ensure that NPM and/or Yarn is installed
on your machine. If you are not sure we recommend you to [install NPM] 
or [install Yarn].

```bash
npm --version
```

### PHP

The STA-Laravel Bulma is a [PHP] package, hence you must ensure that 
you have installed **PHP equal or above version 7.2.5** ([`≥7.2.5`]).

```bash
php --version
```

Listed below you will find the required PHP extensions. Please use the 
[`php -m`] command to check if the following PHP extensions are enabled:

☑ [**BCMath PHP Extension**](https://www.php.net/manual/en/book.bc.php)  
☑ [**CType PHP Extension**](http://php.net/manual/en/book.ctype.php)  
☑ [**JSON PHP Extension**](https://www.php.net/manual/en/book.json.php)  
☑ [**MBString PHP Extension**](https://www.php.net/manual/en/book.mbstring.php)  
☑ [**OpenSSL PHP Extension**](http://php.net/manual/en/book.openssl.php)  
☑ [**PDO PHP Extension**](https://www.php.net/manual/en/book.pdo.php)  
☑ [**Tokenizer PHP Extension**](https://www.php.net/manual/en/book.tokenizer.php)  
☑ [**XML PHP Extension**](https://www.php.net/manual/en/book.xml.php)  

Installation
--------------------------------------------------------------------------------

### Step-01: Use Composer

Lets begin to require the STA-Laravel Bulma Composer dependency within 
your project's `composer.json` file:

```bash
composer require sirthxalot/laravel-bulma --dev
```

The [`composer require`] command will download, install and 
autoload all PHP dependencies into the `vendor/` directory.

> *The `Sta\Laravel\FrontEnd\Presets\Bulma\BulmaServiceProvider` 
  is [auto-discovered] and can be used straight out of box.*

### Step-02: Create Backup (optional)

Front-end presets are meant to change the current file structure of your
Laravel application, hence files can be overwritten or removed from the 
system. So please make sure that you backup your Laravel application 
before running the artisan command. Use [Git] to stash or commit your 
latest changes or use any other backup solution you are familiar with.

### Step-03: Run Preset Command

You are now ready to execute the `preset sta-bulma` artisan command:

```bash
php artisan preset sta-bulma
```

The `preset sta-bulma` artisan command will publish the basic implementation
of the preset without authentication features but with Vue.js.

#### Without Vue.js

If you don't want to use [Vue.js][vue] you don't have to. All you need to do
is to add the `--without-vue` option to the `php artisan preset sta-bulma` 
command:

```bash
php artisan preset sta-bulma --without-vue
```

#### Authentication Scaffolding

The authentication scaffolding (login, register, ...) must be enabled 
separately. Use the `--auth` option in order to do so:

```bash
php artisan preset sta-bulma --auth
```

Getting Started
--------------------------------------------------------------------------------

Please [read the official documentation] in order to get your feet wet
with STA-Laravel Bulma. It is the defacto educational resource specifically 
for any newcomer but also for well established experts.

In fact the documentation is is bundled with the project which makes it 
available for offline reading and provides an easy contribution workflow
for custom updates. The documentation is written in [Markdown], build with
[VuePress] and hosted on [GitHub Pages].

Supported Versions
--------------------------------------------------------------------------------

Versions will be supported for a limited amount of time. Please checkout
[our support policy] in order to receive further information.

**PACKAGE VERSION** | **LARAVEL VERSION** | **PHP VERSION** | **SUPPORT**
:------------------ | :------------------ | :-------------- | :----------------:
[1.0][v1.0]         | [7.0][laravel7.0]   | [7.2.5][php7.2.5]   | *yes*

Browser Compatibility
--------------------------------------------------------------------------------

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Samsung | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| IE11, Edge| last 2 versions| last 2 versions| last 2 versions| last 2 versions| last 2 versions| last 2 versions

> *This does not mean that STA-Laravel Bulma cannot be used in older browsers, 
  just that we will ensure compatibility with the ones mentioned above.*

License
--------------------------------------------------------------------------------

This open source package is available under the [MIT license](LICENSE.md).

--------------------------------------------------------------------------------

*© Copyright 2020, Alexander Bösch (<sta.contribution@gmail.com>) - 
All rights reserved.*

*The STA-Laravel community and its products are meant to use in combination
with Laravel products. However **this package is not an official Laravel
product** nor do we have any influence into the framework at all. We are 
just a bunch of web artisans that try to make world a better place. Our credo 
is: "Happy developers write better code!".*

*Please leave a [star on GitHub] or make a [small donation] if you are 
like what you are using. And thank you for using Laravel Bulma such as 
the trust given in our product.*

***«THAT'S ALL FOLKS - HAPPY CODING...»***

<!-- stop editing ... -->

[laravel]:                  https://laravel.com/docs/7.x/
[front-end presets]:        https://laravel.com/docs/7.x/frontend#introduction
[bulma]:                    https://bulma.io/
[vue]:                      https://vuejs.org/

[`composer self-update`]:   https://getcomposer.org/doc/03-cli.md#self-update-selfupdate-
[laravel mix]:              https://laravel.com/docs/7.x/mix#introduction
[php dependencies]:         https://packagist.org/
[install npm]:              https://nodejs.org/en/
[install yarn]:             https://classic.yarnpkg.com/en/docs/install
[node.js]:                  https://nodejs.org/en/
[npm]:                      https://www.npmjs.com/
[yarn]:                     https://classic.yarnpkg.com/
[`php -m`]:                 https://www.php.net/manual/en/function.extension-loaded.php
[`≥7.2.5`]:                 https://www.php.net/downloads.php
[php]:                      https://www.php.net/

[`composer require`]:       https://getcomposer.org/doc/03-cli.md#requires
[auto-discovered]:          https://laravel.com/docs/6.x/packages#package-discovery
[git]:                      https://git-scm.com/

[read the official documentation]: https://sirthxalot.github.io/laravel-bulma
[markdown]:                 https://vuepress.vuejs.org/guide/markdown.html#markdown-extensions
[vuepress]:                 https://vuepress.vuejs.org/
[github pages]:             https://pages.github.com/

[our support policy]:       https://github.com/sirthxalot/laravel-bulma/blob/master/.github/SUPPORT.md

[v1.0]:                     https://github.com/sirthxalot/laravel-bulma/tree/1.0
[laravel7.0]:               https://github.com/laravel/framework/tree/7.x
[php7.2.5]:                 https://www.php.net/downloads.php

[star on github]:           https://github.com/sirthxalot/laravel-bulma/
[small donation]:           https://www.paypal.com/paypalme2/AlexanderB734/5CHF
