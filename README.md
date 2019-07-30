# How To Add An OSRAM Smart+ Plug To HomeKit With Homebridge And The Philips Hue Bridge

1. Plug the OSRAM Smart+ Plug into a power outlet.

2. In the Philips Hue app, open the Light Setup.

3. Add the OSRAM Smart+ Plug as a new light and change its name.

4. Add the Homebridge plugin `homebridge-hue`  to your configuration and restart the Homebridge server.

5. In the server's terminal, enter `sudo ph -H X.X.X.X -u ABC outlet -v`, where `X.X.X.X` is the Philip Hue bridge's IP address and ABC is the password created while restarting the Homebridge server with `homebridge-hue` enabled for the first time.

6. In the Home app on your iPhone, change the device type of the OSRAM Smart+ Plug to outlet.
