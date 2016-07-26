# 2016-cherub-timeline
Cherubs through the years timeline and alumni profiles

https://medillcherubs.github.io/2016-cherub-timeline/

Paste this into your Wordpress post:

```
<div id="cherub-timeline"></div>
<script> var pymParent = new pym.Parent("cherub-timeline", "//medillcherubs.github.io/2016-cherub-timeline/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-cherub-timeline/edit/gh-pages/index.html -->
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
