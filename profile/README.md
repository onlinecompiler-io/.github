# OnlineCompiler.io

[OnlineCompiler.io](https://onlinecompiler.io/?utm_source=github&utm_medium=repo&utm_campaign=org-profile) is a code execution API. You send source code and a compiler id, and get the output back from a fresh sandbox with no network, 512 MB of memory by default (up to 2 GB on the Pro and Business plans) and a 30 second limit. It runs 46 languages, can judge a program against test cases, and is also available as an MCP server, a WebSocket, an embeddable editor, and Judge0-, Piston- and Jobe-compatible endpoints.

Free up to 100,000 runs a month, commercial use included, no credit card. Get a key at https://api.onlinecompiler.io/compilers/api-keys/ .

```bash
curl -X POST https://api.onlinecompiler.io/api/run-code-sync/ \
  -H "Authorization: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"compiler": "python-3.14", "code": "print(1 + 1)"}'
```

## Repositories

| Repository | What it is |
|---|---|
| [onlinecompiler-mcp](https://github.com/onlinecompiler-io/onlinecompiler-mcp) | The MCP server, for Claude, ChatGPT, Gemini CLI, Cursor, Codex and others |
| [onlinecompiler-python](https://github.com/onlinecompiler-io/onlinecompiler-python) | The Python client: `pip install onlinecompiler` |
| [onlinecompiler-node](https://github.com/onlinecompiler-io/onlinecompiler-node) | The Node client: `npm install onlinecompiler` |
| [react-code-editor](https://github.com/onlinecompiler-io/react-code-editor) | A React code editor with a Run button |
| [online-judge-starter](https://github.com/onlinecompiler-io/online-judge-starter) | A LeetCode-style practice site in Next.js |
| [classroom-autograder](https://github.com/onlinecompiler-io/classroom-autograder) | A GitHub Classroom autograding replacement |

## Links

- [Docs](https://onlinecompiler.io/docs?utm_source=github&utm_medium=repo&utm_campaign=org-profile)
- [Pricing](https://onlinecompiler.io/pricing?utm_source=github&utm_medium=repo&utm_campaign=org-profile)
- [Changelog](https://onlinecompiler.io/changelog?utm_source=github&utm_medium=repo&utm_campaign=org-profile)
- [Status](https://status.onlinecompiler.io)
