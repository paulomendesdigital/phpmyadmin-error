# ERROR Warning in ./libraries/plugin_interface.lib.php#551

Open the file at the path below
```
/usr/share/phpmyadmin/libraries/plugin_interface.lib.php
```

Search de line below
```
if ($options != null && count($options) > 0) {
```

Change by
```
if ($options != null && count((array)$options) > 0) {
```
