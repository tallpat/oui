# oui
OUI Lookups from WSL Ubuntu cli

Modified code from https://unix.stackexchange.com/a/248775 to function on Win10 WSL version of an Ubuntu 20.04 installation


Requirement:

Lynx - text based web browser 
```
$sudo apt install lynx -y
```

Install:

copy to /bin 
```
$sudo cp oui /bin/oui
```

make executable 
```
$sudo chmod +x /bin/oui
```


Run:

To run an OUI lookup, type "oui xx:xx:xx:xx:xx:xx" where the x's are the MAC address to lookup (input must be >=6 digits)


Sample:
```
$oui b8:78:26

B87826     (base 16)            Nintendo Co.,Ltd
```
