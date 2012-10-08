# wTimer.js

A simple JavaScript timer that gives consistent intervals across all browsers.


## Examples

Initialize timer:

```html
<input type="button" value="Start" onclick="timer.start();"/>
<input type="button" value="Stop" onclick="timer.stop();"/>

<div id="wTimer"></div>

<script type="text/javascript">
    var timer = new wTimer({
        fps:1,
        run: function()
        {
            document.getElementById('wTimer').innerHTML += '<div>timer</div>';
        }
    });
</script>
```


## License

MIT licensed

Copyright (C) 2011-2012 Websanova http://www.websanova.com