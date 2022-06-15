# opto_eVOLVER

## Overview

-> Why what
-> Paper link


### Setting up (Ubuntu 20.04.4):

- install npm
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install npm
```
- update node to v17.6.0 and nodejs to v10.19.0 (at least) 
```
node -v
nodejs -v
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
sudo n latest
```
- install [Node-red](https://nodered.org)
```
sudo npm install -g --unsafe-perm node-red
```
- launch Node-RED
```
node-red
```
Look for "Server now running at http://127.0.0.1:1880/". <br/>
Copy Paste this URL (might change) in your favorite web browser.

- Install packages needed for the code via the palette:
  - node-red-contrib-configurable-interval
  - node-red-contrib-counter
  - node-red-contrib-pid
  - node-red-contrib-simpletime
  - node-red-dashboard
  - node-red-node-serialport
  - node-red-node-arduino


## Copyright and License

Copyright &copy; 2022 Sylvain Pouzet

Citation : ...

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and  noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.
