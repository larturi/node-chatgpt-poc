# Chat GPT PoC

## Local

```bash
npm instal

npm start
```

## Test endpoint

```bash
curl -X POST \
  http://localhost:5000/ask \
  -H 'Content-Type: application/json' \
  -d '{ "prompt": "What is the typical weather in Dubai?" }'
```
