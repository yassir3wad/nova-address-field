```shell
GOOGLE_PLACES_API_KEY=############################
```

## Usage

```php
use DigitalCloud\AddressField\AddressField;
// ....

AddressField::make('Address'),

//You can enable lat and lng inputs:
AddressField::make('Address')
          ->withLatLng(),

//You can enable map picking address:
AddressField::make('Address')
        ->withMap(),

//You can set the init location and zoom for the map:
AddressField::make('Address')
        ->withMap()->initLocation('24.6', '46.7')->zoom(5),

```