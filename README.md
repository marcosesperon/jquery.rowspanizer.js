# jquery.rowspanizer.js
Dynamic rowspan based on the content of the table

![Example](http://i.imgur.com/qLRHlzV.png)

### Demo

<http://codepen.io/marcosesperon/pen/MyWNGx>
<br>An example with headers:<br>
<https://codepen.io/saier00/pen/jOOxPVB>

### jQuery

Use the plugin as follows:

```js
$('table').rowspanizer();
```

By default, `vertical-align: top` css style will be added. You can override default by passing the `vertical_align` option:
```js
$('table').rowspanizer({vertical_align: 'middle'});
```

You can define columns to rowspanize:

```js
$('table').rowspanizer({columns: [0,1,2]});
```

## Notes

* Requires jQuery 1.7+.

## License

This plugin is available under [the MIT license](http://mths.be/mit).
