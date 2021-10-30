# shd
simple html dom

orginal docs : https://simplehtmldom.sourceforge.io/

useage :

composer require vladimirnetworks/shd
```
<?php
include("vendor/autoload.php");
use vladimirnetworks\htmlparser\shd;

$dom = shd::str_get_html("<div>vladimir</div>");
echo $dom->find("div",0)->innertext;
// ....
?>
```
