Local browser support for [web-component-tester][1].

This is currently a dependency of WCT, and tested via it.

[1]: https://github.com/Polymer/tools/tree/master/packages/web-component-tester
[3]: https://github.com/Polymer/tools


config: selenium grid   
```json
"remote": {
    "disabled": false,
    "browsers": [
        "chrome"
    ],
    "port": 5566,
    "hostname": "127.0.0.1"
}'
```