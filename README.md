# zoneinfo-npm
This package provides updated IANA zoneinfo files for timezone handling.
Some systems do not have all timezones installed, nor updated,  while some systems do not use it by default (like Windows, embeded systems, etc).

## Installation
Please consider install this package globally, otherwise your project may get supersized with data about every timezone history of all over the world.
```
npm install zoneinfo-npm -g
```
By installing this package globally, all included timezones will be available for any project to use, and no additional size will be added to them.


## Database
This version is equivalent to IANA tzdb 2023c (Released 2023-03-28)

## Updates
There is the intention to keep this package up to date with IANA Timezone Database releases.
Did I miss a Release? Issue me :D

You may keep your database updated by periodically running
```
npm install zoneinfo-npm@latest -g
```