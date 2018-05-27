### Suport for debian jessie
# NodeJS Linux Installer for debian jessie and the android app gnu root debian
This is an universal NodeJS installer for Linux.[version modified to support debian jessie 8 ]
I don't take any responsibilities if you blow your system up!

### Installing
``` uninstall nodejs

    running anyuser@anyuser:~$ sudo apt-get purge --auto-remove nodejs
    
    or manually completely uninstall node + npm is to do the following:

    -go to /usr/local/lib and delete any node and node_modules
    -go to /usr/local/include and delete any node and node_modules directory
    -if you installed with brew install node, then run brew uninstall node in your terminal
    -check your Home directory for any local or lib or include folders, and delete any node or node_modules from there
    -go to /usr/local/bin and delete any node executable
    -check running node or nodejs on the cli to be sure that nodejs its completely absent
    
    after that we will proceed to download the following script
    
    run the following command in the cli

    anyuser@anyuser:~$ git clone https://gist.github.com/38fb534ef04e2ead7c4015c32639ea24.git
    
    then

    locate the file node-install.sh and run it as sudo
    
    anyuser@anyuser:~$ sudo chmod 744 node-install.sh
    
    anyuser@anyuser:~$ sudo ./node-install.sh
    
    wait a few minutes while the script search for the correct node version for gnu root debian
```

### Contributing
Just create a fork and please contribute all your improvements back here!

### License
MIT

Thanks for all Contributions

### forked and modified by mrgab0 from ```https://github.com/taaem/nodejs-linux-installer```
