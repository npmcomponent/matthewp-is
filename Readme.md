*This repository is a mirror of the [component](http://component.io) module [matthewp/is](http://github.com/matthewp/is). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewp-is`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# is

  egal function, based on ES6 Object.is

## Installation

    $ component install matthewp/is

## API

```javascript
var is = require('is');
x = NaN;
x === x; // => false
is(x, x); // => true
```

## License

  MIT
