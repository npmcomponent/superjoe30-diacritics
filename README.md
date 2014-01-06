*This repository is a mirror of the <http://component.io> module <http://github.com/superjoe30/diacritics>. It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/superjoe30-diacritics`.*

# diacritics

  remove diacritics from strings

  useful when implementing some kind of search or filter functionality.

## Node.js Installation

    $ npm install diacritics

## Component Installation

    $ component install superjoe30/diacritics

## API

```js
var removeDiacritics = require('diacritics').remove;
console.log(removeDiacritics("Iлｔèｒｎåｔïｏｎɑｌíƶａｔï߀ԉ"));
// prints "Internationalizati0n"
```

## License

  MIT
