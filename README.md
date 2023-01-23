## Installation

- Install packages on root folder by running `npm install` or `yarn install`.
- Install packages in client folder by going to `/client` and running `npm install` or `yarn install`.

## The easy way (recommended)

### In dev:

Make sure to go to `/client` and run `yarn build` to serve the latest changes.

Run `node webserver.js` and open `https://localhost:8080` to see the project.

If you want to use a different port run `node webserver.js PORT_NUMBER`, ex. `node webserver.js 8081`

### In production

If you have downloaded the Raspberry Image, you don't need to setup anything.

1. Connect to the Wifi with name: `recurBoy`, the password is: `recurboy`
2. Open http://192.168.4.1:8080

And you are be ready to go.

## The hard way

If you would like to do the setup yourself refer to these instructions:

- [Setting up the Raspberry Pi, Node & Osc servers](./docs/Pi_Setup.md)
- [Setting up the client](./client/README.md)

## Source:

To configure the raspberry Pi to switch between Access Point and WLAN modes, [check this guide](https://github.com/Autodrop3d/raspiApWlanScripts/blob/master/setup_wlan_and_AP_modes.sh).
