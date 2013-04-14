momentjs-web-lang
=================

[momentjs](http://momentjs.com) language packs, ready for the web.

The NodeJS "require" mention has been stripped.

```bash
> igrep -l "require('../moment')" . |  xargs -i% sed -i -e "s/require('\.\.\/moment')/moment/" %
```
