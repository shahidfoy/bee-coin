# install

nodejs: https://nodejs.org/
run

```
npm install
```

to install package libraries

create a local server using:

```
npm run dev
```

create p2p servers using:

```
HTTP_PORT=3002 P2P_PORT=5002 PEERS=ws://localhost:5001 npm run dev
```

increment ports and add others to PEERS
