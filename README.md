# jQuery UI AMD Bundle for Symfony2

## Current Version

jQuery UI 1.9.2

## Requirements

jQuery core

## Installation

### Add bundle to your composer.json file

``` js
// composer.json

{
    "require": {
		// ...
        "icode4food/jqueryui-bundle": "*"
    }
}
```

### Add bundle to your application kernel

``` php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Icode4food\JqueryUiBundle\Icode4foodJqueryUiBundle(),
        // ...
    );
}
```

### Download the bundle using Composer

``` bash
$ php composer.phar update icode4food/jqueryui-bundle
```

## Usage

Refer to the desired files in your AMD module

## Licenses

Refer to the source code of the included files for license information
