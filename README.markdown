LESSYUI.PHP
===========

This is a wrapper for the lessphp project and the CSS YUI compressor.

1. Include file in your web project under ie. 'lib/'
2. Add this to your htaccess: RewriteRule (.*)(\.less) lib/lessyui.php?f=$1.$2 [L]
3. Write some .less files and directly call it from your HTML




