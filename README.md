# Sunday Relay — Web

Frontend for sundayrelay.com. Static HTML hosted on Cloudflare Pages.

## How it deploys

Push to main → Cloudflare Pages auto-deploys within ~60 seconds.

## API

The Sunni chat drawer calls the Sunday Relay API at:
https://api.sundayrelay.com/chat/sunday-relay

Local dev falls back to http://localhost:4000 automatically.