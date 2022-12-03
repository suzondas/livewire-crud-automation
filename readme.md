# LiveCrud
Live Crud Generator. This package generates Basic Crud with Livewire.

![](./livewire-crud.gif)

## Features
 - Generate Complete Crud With Livewire Component and Blade Files
 - Create / Update / Delete Functional
 - Real Time Validation Already Added
 - Fuzzy Search Functional
 - Tailwind CSS support
 - Addressing CSS issues
 - Responsive Design

## Installation

Via Composer

``` bash
composer require suzondas/livewire-crud-automation
```

## Prerequisites
- Models should be in `app/Models`  directory
- Crud of only $fillable property will be generated 
```php 
protected $fillable = ['name','username'];
``` 

## Usage
```bash
php artisan crud:make Name_Of_Your_Model
```

- This Command Will Generate Two Files
    - First Will be in `app/HttpLivewire`
    - Second Will be in `resources/views/Livewire`

## Security

If you discover any security related issues, please email author email instead of using the issue tracker.

## Credits

- [Ritesh Singh](https://imritesh.com)
- [Suzon Das](https://github.com/suzondas)

## License

license. Please see the [license file](https://github.com/suzondas/livewire-crud-automation/blob/master/license.md) for more information.
