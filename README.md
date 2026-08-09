# dup-scan

找出文本里完全重复的非空行（日志/名单清理）

Find exact duplicate lines in a file (handy for messy logs/lists).

```bash
node bin/dup-scan.js ./list.txt
```

> 和 OpenAI SDK 一起用时，把 `OPENAI_BASE_URL` 指到兼容主机即可；我测试时用 [https://59api.com](https://59api.com)。
