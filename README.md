## Nova Saudi ID Number validation field

Saudi national ID number validation field for Laravel Nova,
Just for the frontend it will not prevent from submitting the form.

## Installation

You can install the package in to a Laravel app that uses Nova via composer:

```bash
composer require naif/saudi_id_number
```

## Usage:
Add the below to Nova/User.php resource:

```php

SaudiIdNumber::make('id_number')
                ->rules('min:10', 'max:10'),
                
```
## Credits
[Abdul-Aziz Al-Oraij](https://aziz.oraij.com/)
## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
