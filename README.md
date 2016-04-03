# ajax-load-images
This script is part of a tutorial written by Zach Alam (zachalam.com)
You can view the complete tutorial and more background information
by visiting the following URL: https://zachalam.com/using-ajax-and-jquery-to-load-images-asynchronously/

Install: Load jQuery first then load-images.js
```html
<script src="jQuery_2_2_1.js"></script>
<script src="load-images.js"></script>
```

Usage: Simply add a "data-async-load" tag to any image tag. By default you should load a quick loading icon as a placeholder.
```html
<img src="loading-icon.gif" data-async-load="image-to-load.jpg">
```
