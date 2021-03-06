
# angular-filesystem

  Component that interacts with the filesystem

## Installation

  Install with [component(1)](http://component.io):

    $ component install enome-components/angular-filesystem

## API

```js
require('angular-file-manager');
var module = angular.module('my-app', ['file-manager']);
```

```html
<file-manager url='"/fileserver"' selected='selected'></file-manager>
```

- url: server end-point to crud files and dirs
- selected: array with the paths of the files and dirs

## Example

```sh
make build
cd example
npm install
node app.js
```

or

```sh
git clone https://github.com/enome-components/angular-file-manager.git && cd angular-file-manager && make build && cd example && npm install && node app.js
```

## License

  MIT
