修改 thc-ssl-dos 工具

编译： gcc -o thc-ssl-dos src/thc-ssl-dos.c  -lssl -lcrypto

删除了15秒等待和当不支持renegotiation时重连握手