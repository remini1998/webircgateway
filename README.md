# websocketgateway
Simple websocket gateway to IRC networks

### Overview
* Multiple servers, non-tls / tls / multiple ports
* Multiple websocket engine support
    * Websockets
    * SockJS
* Multiple upstream IRC servers in a round robin fashion
* WEBIRC support

### Running
Once compiled and you have a config file set, run `./websocketgateway --config=config.conf` to start the gateway server. You may reload the configuration file without any downtime by sending SIGHUP to the process.
