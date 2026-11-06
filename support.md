---
title: "Support"
permalink: /support/
---

# Kismet for iPhone and Apple TV: Support

Kismet for iPhone and Apple TV is a client for your own [Kismet](https://www.kismetwireless.net/) wireless sensor. It needs a Kismet server that your device can reach. To look around without one, choose **Try the demo** on the welcome screen.

## Connecting

1. In Kismet's web UI, go to **Settings > API Keys** and create a token. The `readonly` role is enough.
2. In the app, choose **Connect to my Kismet server**, then enter the server's address and the token. A user name and password also work.

## Common problems

**The app can't reach my server.** Check that your device is on the same network or VPN as the server, and that the address and port are right. Kismet's default port is 2501.

**An http address is refused.** Plain http works only on the local network: IP addresses, `.local` names and names without dots. Anywhere else the server must use https.

**Nothing appears on the local network.** Allow local network access in iOS Settings under Privacy & Security > Local Network.

**The aircraft map is empty.** Aircraft need an ADS-B source on your Kismet server. To show distances, the server needs a GPS fix, or you can enter its location in the app's settings.

**I can't log in.** Check that the token still exists in Kismet's web UI, then enter it again in the app's settings.

## Contact

Email [hello@defiantlabs.io](mailto:hello@defiantlabs.io). Please include your app version and Kismet version.

[Privacy policy](../privacy/)
