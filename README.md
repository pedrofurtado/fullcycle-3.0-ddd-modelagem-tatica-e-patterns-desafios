```bash
docker container run --rm -it -w /app -v $(pwd):/app node:18 bash
  npm install
  npm run test
```
