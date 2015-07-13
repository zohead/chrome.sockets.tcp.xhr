# XMLHttpRequest using Chrome sockets #

This is a XMLHttpRequest class using chrome.sockets.tcp on Chrome browser.

Forked from <https://github.com/codeinchaos/chrome.sockets.tcp.xhr>.

Please check documents from <http://chromesocketstcpxhr.readthedocs.org/en/latest/>.

## Enhancements ##

* Get full response data, instead of only getting first segument data.
* Add content length checking from response header.
* Support only get HTTP 304 redirect URL.
* Support first received data timeout.

