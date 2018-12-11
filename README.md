# [![ViaCRYPT](assets/img/logo.png)](https://viacry.pt/)

One time read messaging system. You can try it at [viacry.pt](https://viacry.pt/).

## Quick Start

- this repository is forked from viacrypt/viacrypt [https://github.com/vialink/viacrypt]
- bower.json configuration is changed according to @daveschaefer's pull request because of changed URLs for crypto-js
- default.js IP changed to 0.0.0.0

instead of changing default.js, create local.js 
    module.exports = {
        baseurl: '//localhost:8001'
    }
this overwrites the settings from default.js

