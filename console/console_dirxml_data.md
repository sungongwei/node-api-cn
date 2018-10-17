<!-- YAML
added: v8.0.0
changes:
  - version: v9.3.0
    pr-url: https://github.com/nodejs/node/pull/17152
    description: "`console.dirxml` now calls `console.log` for its arguments."
-->
* `...data` {any}

This method calls `console.log()` passing it the arguments received.
Please note that this method does not produce any XML formatting.

此函数调用'console.log()'并传递其接收的参数，
注意此函数并不输出任何XML格式

