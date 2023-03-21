# node.js-installation-on-hosting

1. SSH setup ON

2. Two Software Download Putty and windowse installer and exe-software

3. Open Putty Software
   - enter IP address
   - port number
   - password and clikc to start
   
4. now terminal open atomatically   

5. enter cpanel username and password

6. command install node.js
```
wget https://nodejs.org/dist/v18.15.0/node-v18.15.0-linux-x64.tar.gz
```

7. unzip command for node.js
```
tar xvzf node-v18.15.0-linux-x64.tar.gz
```

8. mv command
```
mv node-v18.15.0-linux-64 nodejs
```
9. create folder
```
makdir ~/bin
```
10. copy coommand
```
cp nodejs/bin/node ~/bin
```
11. change directory
```
cd ~/bin

//for start
ln -s ../nodejs/lib/node_modules/npm/bin/npm -cli.js npm

//version
node --version
```
