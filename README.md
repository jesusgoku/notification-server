Notification Server
===================

Generic notification server for use in your proyects for implement
notifications in real time.

Usage
-----

Create configuration file:

```bash
cp config.dist.js config.js
```

Run server:

```bash
npm start
```

Open your browser on:

```
http://localhost:3001
```

> Important: port depend port configure on configuration file.

Testing sensing a notification with cURL:

```bash
curl -X POST -H "Content-Type: application/json" -d '{ "event": "testing", "data": "Hello World" }' http://localhost:3001/notification
```
