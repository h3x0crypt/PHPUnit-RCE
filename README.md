# PHPUnit-RCE
PHPunit Remote code execution
Infected Versions : before 4.8.28 and 5.x before 5.6.3

Util/PHP/eval-stdin.php in PHPUnit before 4.8.28 and 5.x before 5.6.3

It allows remote attackers to execute arbitrary PHP code via HTTP POST 
data beginning with a "<?php " substring, as demonstrated by an attack 
on a site with an exposed /vendor folder, i.e., external access to 
the /vendor/phpunit/phpunit/src/Util/PHP/eval-stdin.php URI.

