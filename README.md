# HTTP2-Node-Server

First steps using http2

changes 
  - Multiplexing: multiple request at the same time.
  - Server push: Server can push assets (CSS, JS, Images) before the app know that he needed.
  - Stream priority: priority in some assets, (eg. first HTML).
  - Header Compression: Not more duplicate headers.
  - Mandatory encryptation: really is not required but the browser only implements H2 over HTTPS.
  
  For know not with the current implementation for express (only in express5) but with spdy.
  
