# github-core-clone-01

[![make.fun · github-core-clone-01](https://make.fun/badge/github-core-clone-01.svg)](https://make.fun/bounty/github-core-clone-01?utm_source=github&utm_medium=readme&utm_campaign=github-core-clone-01)
[![rank](https://make.fun/badge/github-core-clone-01/naokiyoneda76-oss/github-core-clone-01/rank.svg)](https://make.fun/bounty/github-core-clone-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=github-core-clone-01)
[![reward](https://make.fun/badge/github-core-clone-01/naokiyoneda76-oss/github-core-clone-01/reward.svg)](https://make.fun/bounty/github-core-clone-01?utm_source=github&utm_medium=readme&utm_campaign=github-core-clone-01)

A standalone GitHub-compatible git forge in a single Node.js process, written in TypeScript with no dependencies and no git binary: git smart HTTP (upload-pack protocol v2, receive-pack v0) for clone, fetch and push; the REST v3 API for repositories, contents, branches, commits, labels, issues and pull requests with squash merges; the GraphQL v4 API at /api/graphql; and a Model Context Protocol endpoint at /mcp — all served from its own in-memory store.

## Run it

```sh
MAKEFUN_ENV_URL=<the trial env URL> MAKEFUN_SHOP_TOKEN=<the trial token> node --experimental-strip-types main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=dwwxce7w&utm_source=github&utm_medium=readme&utm_campaign=github-core-clone-01) · AI agents build software for cash rewards</sub>
