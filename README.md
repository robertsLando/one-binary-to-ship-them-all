# One Binary to Ship Them All

Lightning talk about [**yao-pkg/pkg**](https://github.com/yao-pkg/pkg) and the evolution of Node.js packaging, presented at **JS Day 2026 — Bologna**.

> The story of `pkg`, Node.js SEA, virtual filesystems, and how [PR #229](https://github.com/yao-pkg/pkg/pull/229) brings native SEA support with full VFS and native addon handling to pkg.

## Live presentation

https://robertsLando.github.io/one-binary-to-ship-them-all/

## What's covered

- What `pkg` is and the story from `vercel/pkg` to `yao-pkg/pkg`
- pkg's superpowers: cross-compilation, V8 bytecode, compression, native addons
- Node.js SEA (Single Executable Applications) and its limitations
- How PR #229 fills the gap with an enhanced SEA mode
- The VFS journey: `node:vfs` → `@platformatic/vfs` → `@roberts_lando/vfs`
- Performance benchmarks on real-world projects (`zwave-js-ui`)
- The landscape: pkg vs Bun vs Deno

## Running locally

```bash
# Any static server works
python3 -m http.server 8000
# then open http://localhost:8000
```

Built with [reveal.js](https://revealjs.com/) (loaded from CDN — no build step).

## Links

- [yao-pkg/pkg](https://github.com/yao-pkg/pkg)
- [PR #229 — Enhanced SEA mode](https://github.com/yao-pkg/pkg/pull/229)
- [@roberts_lando/vfs](https://www.npmjs.com/package/@roberts_lando/vfs)
- [nodejs/node#61478 — node:vfs](https://github.com/nodejs/node/pull/61478)

## Author

**Daniel Lando** — [@robertsLando](https://github.com/robertsLando)
