# excalidraw-room-protoype
## Steps to deploy Collaboration server
1) git clone https://github.com/hussainlal/excalidraw-room-protoype.git
2) npm init
3) npm run build
4) node dist/index.js
5) Server should be up and running at port 80

## Steps to add server details to Excalidraw
1) git clone https://github.com/excalidraw/excalidraw.git
2) Update REACT_APP_SOCKET_SERVER_URL in .env file to point to localhost:80
3) Initialize the server using the steps: https://github.com/excalidraw/excalidraw#install-the-dependencies
