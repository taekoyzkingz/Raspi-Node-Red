# How to Install NODE-RED in Raspberry PI

- Install Node-RED
```bash
$ bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```
- Enable Service Node-RED
```bash
$ sudo systemctl enable nodered.service
```
- Reboot Raspberry PI
```bash
$ sudo reboot
```
