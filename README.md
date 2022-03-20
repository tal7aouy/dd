# dd

This library will add the `dd` and `dump` helpers to your PHP application.

⚡️ Install

Run:

```sh
composer require tal7aouy/dd
```

✅ Usage

```php
$arr = ['a'=>'a','b'=>b];
dd($arr);
// or 
dump($arr);
```
🤓 output:
```json
^ array:2 [▼
  "a" => "a"
  "b" => "b"
]
```


🚀 For Laravel

[Laravel](http://laravel.com) already have the `dd` function in its helpers.
The `dd` function from this package is equal to the one in Laravel.


**dd** was created by **[tal7aouy](https://github.com/tal7aouy)** under the **[BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)**.
