Bootstrap 4 grid for Magento 2. Use it if you only need grid columns and don't want to use whole bootstrap less and JS files.

This is a less mixin that generates col-* bootstrap grid columns, container and row base styles.

Copy the Less file to your vendor/theme/web/css/source path and import it to your sources.less file

Then:
grunt exec:your-theme
grunt less:your-theme

Use it like Bootstrap:
```
<div class="container">
  <div class="row">
    <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3 col-xl-2">
      ...
    </div>
  </div>
</div>
```
