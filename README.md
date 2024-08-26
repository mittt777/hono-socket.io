# Hono + Socket.IO

This is a example of how to use Hono with Socket.IO based on the [Socket.IO chat tutorial](https://socket.io/docs/v4/tutorial/introduction).
The Socket.IO instance is available in Hono via the `io` property in the context.

## Usage

1. Install dependencies and start the server

```bash
npm install
npm run dev
```

2. Open two tabs at http://localhost:3000

3. Start chatting

4. (optional) Send a message via POST

```bash
curl -X POST -H "Content-Type: application/json" -d '{"message": "Hello from Hono!"}' http://localhost:3000/message
```
