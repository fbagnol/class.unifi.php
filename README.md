# class.unifi.php

Example of usage:
```
$unifi=new unifiapi("username","password","https://<ip_of_unifi>:84443");
$unifi->login();
$unifi->authorize_guest("mac adress",60)
```
