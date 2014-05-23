# fis-postpackager-modjs

a postpackager plugin for fis to process map.json and create map.js for modjs

## usage

    $ npm install -g fis-postpackager-yymodjs
    $ vi path/to/project/fis-conf.js

```javascript
//file : path/to/project/fis-conf.js
fis.config.set('modules.postpackager', 'yymodjs');
//settings
fis.config.set('settings.postpackager.modjs.subpath', 'pack/map.js');
```