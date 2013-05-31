# connect-fonts-ubuntucondensed

Ubuntu Condensed fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-ubuntucondensed");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/ubuntucondensed-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* ubuntucondensed-regular

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/ubuntucondensed-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin
* en

5. Set your CSS up to use the new font by using the "Ubuntu Condensed" font-family.
```
    body {
      font-family: 'Ubuntu Condensed', 'sans-serif', 'serif';
    }
```

## Font Info
Ubuntu Condensed

* Copyright: Copyright 2011 Canonical Ltd.  Licensed under the Ubuntu Font Licence 1.0
* Trademark: Ubuntu and Canonical are registered trademarks of Canonical Ltd.
* Designer: Dalton Maag Ltd
* Designer URL: http://www.daltonmaag.com 
* Vendor: Dalton Maag Ltd
* Vendor URL: http://www.daltonmaag.com/

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-ubuntucondensed
* Repo: https://github.com/shane-tomlinson/connect-fonts-ubuntucondensed

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.0 of the Ubuntu Font License

  http://font.ubuntu.com/ufl/ubuntu-font-licence-1.0.txt

