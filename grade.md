# Autograding Report (Failed)

An error occurred during autograding:

```
Server exited early with code 1
```

## Server Logs
Here is the last output from the server before failure:

```
◇ injected env (6) from config/config.env // tip: ⌘ multiple files { path: ['.env.local', '.env'] }
Server running in   development  mode on port  5000
node:events:505
    throw er; // Unhandled 'error' event
    ^

Error: listen EADDRINUSE: address already in use :::5000
    at Server.setupListenHandle [as _listen2] (node:net:2324:16)
    at listenInCluster (node:net:2433:12)
    at Server.listen (node:net:2558:7)
    at app.listen (/Users/nop_mick/Documents/GitHub/503cp69-a7-2-mickdoctordev/node_modules/express/lib/application.js:605:24)
    at Object.<anonymous> (/Users/nop_mick/Documents/GitHub/503cp69-a7-2-mickdoctordev/server.js:25:20)
    at Module._compile (node:internal/modules/cjs/loader:1934:14)
    at Object..js (node:internal/modules/cjs/loader:2074:10)
    at Module.load (node:internal/modules/cjs/loader:1656:32)
    at Module._load (node:internal/modules/cjs/loader:1448:12)
    at wrapModuleLoad (node:internal/modules/cjs/loader:261:19)
Emitted 'error' event on Server instance at:
    at emitErrorNT (node:net:2412:8)
    at process.processTicksAndRejections (node:internal/process/task_queues:90:21) {
  code: 'EADDRINUSE',
  errno: -48,
  syscall: 'listen',
  address: '::',
  port: 5000
}

Node.js v26.7.0

```
