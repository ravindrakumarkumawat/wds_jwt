# JWT Authentication

- Creating Node.js authentication middleware
- Using refresh tokens with JWT
- Authenticating users with JWT
- Invalidating refresh tokens to log users out
- How to use JWT securely

# Installation

Use [npm](https://www.npmjs.com/) 

```bash
npm init
```

```bash
npm i express jsonwebtoken dotenv
```

```bash
npm i --save-dev nodemon
```
for creating secret Token using terminal

```bash
node
require('crypto').rendomBytes(64).toString('hex')
```