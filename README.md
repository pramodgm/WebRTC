# WebRTC Demo

Video conferencing using WebRTC API.

## Build

Use the package manager [npm](https://www.npmjs.com/) to build.

```bash
npm install bootstrap #Downloading bootstrac CSS libs
npm install ws        #Downloading Webserver libs
npm install
```

## Requirement
1. [NodeJs](https://nodejs.org/en/)
2. Webserver
```bash
sudo npm install -g node-static
OR
sudo npm install http-server -g
```

## Running
Start the Signaling Server First
```bash
node server
```

Then start the web server which you are using.
```bash
static                    #If you are using node-static server (Works only on Local Machine).
OR
http-server ./ -p 8080    #If Using http-server (Use in case if you are accessing from other machines).
```

To access the UI go to http://IP:8080

### Ports Used
8080 Web UI Access

9090 Signaling Server

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.