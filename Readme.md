
# random

  Generate random numbers

## Installation

    $ component install danzajdband/random

## Usage


```js
var rand = require('random');

console.log(rand()); // Returns a Number between 0 and 1.
console.log(rand(1)); // Returns a Number between 1 and 2.
console.log(rand(-6, 38)); // Returns a Number between -6 and 38.
console.log(rand(7, 19, true)); // Returns a Integer between 7 and 38.
```


## API

### random(min = 0, max = min + 1, truncate)
  
Return a random number between `min` and `max`. If truncate is set to `true` return only integer values.


## License

  MIT
