# Bundling non-buildable example

This workspace uses Vite to bundle in non-buildable dependency (`util2`) into the buildable package (`util`).

Run:

```
pnpm nx build util
```

And inspect `packages/util/dist/index.mjs` to see that `util2` is bundlded into the output.
