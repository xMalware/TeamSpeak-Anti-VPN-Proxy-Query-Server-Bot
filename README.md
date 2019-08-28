# TeamSpeak - AntiVPN

I created this system basically for my own projects, it's a small project that helped reduce the number of malicious clients that came to troll on our TeamSpeak server. Following several requests, I decided to make a simple and light version, **free to use**.


# Installation
Installation is quite simple. You can download the [JAR executable application from the binaries page.](https://github.com/xMalware/TeamSpeak-AntiVPN/releases) You can clone this project and build it with Maven for people who want to modify the code or do something much cleaner than that.

## Configuration

Configuration is also very simple. You have a config.json file in the ZIP archive (if you download from binaries) that you can configure very easily, with very few variables :

 - **hostname** : The hostname or IP of the TeamSpeak server you are running
 - **queryPort** : The TeamSpeak server query port (10011 by default)
 - **queryPassword** : The TeamSpeak server query password
 - **virtualServerId** : The virtual server ID (1 by default)
 - **nick** : The TeamSpeak bot name
 - **ipDetectorApiKey** : The API key of the service to detect VPNs. If you do not yet have a key, you can create one at https://ipdetector.info by registering.
The free offer can handle up to 30 requests per minute and may be sufficient for small/medium TeamSpeak servers, otherwise there are paid offers at very affordable prices.
- **banIdentity** : Ban TeamSpeak identity of the user who connects to the TeamSpeak server (default: false)
- **banIp** : Ban TeamSpeak IP of the user who connects to the TeamSpeak server (default: true)
- **banReason** : The ban reason

# Detect VPN Proxy API

I use an official Detect VPN and Proxy API check it out : https://ipwarner.com 
