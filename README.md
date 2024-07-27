## Loan System

### Running on local server

*use pnpm*
- Navigate to client> `pnpm i` >> `pnpm run dev`
- Navigate to server> `pnpm i` >> `pnpm run dev`

*server will be running on Port 5000 and client on 5173*

Note: Add the following environment variables

client
```
VITE_BE_URL=<your-backend-url>
```
server
```
SECRET_KEY=<generated-jwt-key>
CONNECTION_URL=<your-mongodb-url>
```
> generate secret key using `node -e "console.log(require('crypto').randomBytes(64).toString('hex'))"`

