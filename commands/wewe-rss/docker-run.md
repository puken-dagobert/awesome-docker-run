---
repo: "https://github.com/cooderl/wewe-rss"
category: "RSS"
---

# Docker Run Command

```bash
docker run -d \
  -p 4000:4000 \
  -e DATABASE_TYPE=sqlite \
  -e AUTH_CODE=123567 \
  -v $(pwd)/data:/app/data \
  cooderl/wewe-rss-sqlite:latest
```
