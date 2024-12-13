# ChapBaraks.php
https://quera.org/problemset/3405?tab=description
<?php
$n = (int)readline("Enter a number: ");
$thislist = [];
while($n != 0){
	array_push($thislist, $n);
	$n = (int)readline("Enter a number: ");
}
$m = array_reverse($thislist);
echo implode(PHP_EOL , $m);
