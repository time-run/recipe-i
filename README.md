# recept-i
A submission to the [IT-Talents Code Competition](https://www.it-talents.de/foerderung/code-competition/code-competition-10-2020-edeka-digital). 

Native JS-based "What's in my fridge" web application with basic functionallity, barcode scanner and advanced search of recepts. Check out this [live demo](https://www.shot-boehm.com/apps/recipe-i/). 

If you have not received this project by cloning from git, check out the [repository](https://github.com/time-run/recipe-i).

![recipe-i-fridge](/images/recept-i-fridge.png)

## Features

* Basic functions - add, remove items by type in name or scanning barcode
* Search and find recepts by ingredients
* Filter recepts by diet, type and time
* Detailed recipe description with checklist
* Save/Restore items to/from the browser local storage
* Animated graphical user interface

## Implementation

### Project Structure

Folder recipe-i/set contains all css- and js-files, also the fontello font and graphics.

## Dependencies

* [zxing](https://github.com/zxing/zxing) - barcode reader
* [Fontello Font](https://fontello.com/) - fancy font icons
* [Open Food Facts Api](https://world.openfoodfacts.org/) - barcode to product name
* [Spoonacular Api](https://spoonacular.com) - find recepts with api

## Copyright and License

Copyright 2020 Michael Böhm

This project is licensed under GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or any later version.
