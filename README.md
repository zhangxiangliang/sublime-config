# Sublime 编辑器的个人配置

## SublimePhpCsFixer
* 安装 `composer global require friendsofphp/php-cs-fixer`
* 配置 `"config": "/Users/bitmaster/.phpcsfixer"`
* 创建 `~/.phpcsfixer`

```php
<?php

return PhpCsFixer\Config::create()
    ->setRules([
        '@PSR2' => true,
        'array_syntax' => ['syntax' => 'short'],
        'no_unused_imports' => true
    ]);
```

## SublimeLinter
* 配置 `"paths" => "osx"`
