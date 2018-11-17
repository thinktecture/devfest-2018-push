# Advanced Progressive Web Apps: Push Notifications Under Control

Google DevFest Karlsruhe, Duale Hochschule Baden-Württemberg.

Speaker: [Christian Liebel](https://twitter.com/chris_liebel), Thinktecture.

## Setup

### Demo 1 (non-persistent notifications/Notifications API)

1. Run `npx lite-server`
6. Your browser should open. Navigate to [http://localhost:3000/index.0.html](http://localhost:3000/index.1.html) (port may vary, if 3000 is already in use)

### Demo 2 (persistent notifications/Push+Notifications API)

1. On your console, run `npm i`.
2. Go to [https://pwapraxis-push.glitch.me](https://pwapraxis-push.glitch.me) to get VAPID keys.
3. Update `index.1.html` and `server.js` with the according public/private VAPID keys.
4. Run `npm start` to boot up the server.
5. Run `npx lite-server`
6. Your browser should open. Navigate to [http://localhost:3000/index.1.html](http://localhost:3000/index.1.html) (port may vary, if 3000 is already in use)