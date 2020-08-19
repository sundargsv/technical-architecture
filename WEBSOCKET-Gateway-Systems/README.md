# Web Socket Wrapper on Micro services
This is a spring module starter project and once imported into an existing spring boot based
 Micro service application, it'll become an overhead of all the API/ controller endpoints and exposes a single websocket ws:// or wss:// to communicate with all the controllers.

 A websocket wrapper around all the spring controllers / REST API to attain a full-duplex communication whenever possible instead of multiple API calls to the same service.

 # Tool as Gateway
 This tool can also be leveraged later to act as a gateway of all microservices with WSS:// protocol which means having a full-duplex communication with client -> Gateway and making calls to other Micro services with same socket connection
