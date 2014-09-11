# metisMenu [![Build Status](https://secure.travis-ci.org/onokumus/metisMenu.png?branch=master)](https://travis-ci.org/onokumus/metisMenu)

> Easy menu jQuery plugin for Twitter Bootstrap 3

> Now support cdnjs & jsdelivr


## Installation

* [npm](http://npmjs.org/)

```bash
npm install metismenu
```

* [Bower](http://bower.io)

```bash
bower install metisMenu
```

* [Download](https://github.com/onokumus/metisMenu/archive/master.zip)

## Usage

1. Include Twitter Bootstrap StyleSheet

    ```html
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.2.0/css/bootstrap.min.css">
    ```

2. Include metisMenu StyleSheet

    ```html
    <link rel="stylesheet" href="dist/metismenu.min.css">
    ```

3. Include jQuery

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
    ```

4. Include Twitter Bootstrap Script

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.2.0/js/bootstrap.min.js"></script>
    ```

5. Include metisMenu plugin's code

    ```html
    <script src="dist/metismenu.min.js"></script>
    ```

6. Call the plugin
  - Via data attributes

    ```html
    <ul data-toggle="metisMenu">
      <li>
      ...
      ...
    </ul>
    ```
  - Via JavaScript

    ```javascript
      $('.your-menu').metisMenu(options);
    ```

### Options

#### toggle
Type: `Boolean`
Default: `true`

For auto collapse support.

```javascript
  $("#menu").metisMenu({
    toggle: false
  });
```

#### doubleTapToGo
Type: `Boolean`
Default: `false`

For double tap support.

```javascript
  $("#menu").metisMenu({
    doubleTapToGo: true
  });
```


### [DEMO](http://demo.onokumus.com/metisMenu/)

Contains a simple HTML file to demonstrate metisMenu plugin.

### Release History
**DATE**       **VERSION**   **CHANGES**
* 2014-09-11   v1.1.2      re-coded bootstrap style. Enable data-api
* 2014-08-24   v1.1.1      merge AndrewEastwood patch-1 branch
* 2014-07-07   v1.1.0	     Add double tap functionality
* 2014-06-24   v1.0.3	     cdnjs support & rename plugin
* 2014-06-18   v1.0.3        Create grunt task
* 2014-06-10   v1.0.2        Fixed for IE8 & IE9


## Author

metisMenu was made with love by these guys and a bunch of awesome [contributors](https://github.com/onokumus/metisMenu/graphs/contributors).

[![Osman Nuri Okumuş](https://0.gravatar.com/avatar/4fa374411129d6f574c33e4753ec402e?s=70)](http://onokumus.com) |
--- | --- | --- | --- | --- | --- | ---
[Osman Nuri Okumuş](http://onokumus.com) |


## License

[MIT License](https://github.com/onokumus/metisMenu/blob/master/LICENSE)
