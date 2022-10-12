# Logseq Plugin template

A template for Logseq plugins, using Svelte, Vitest, Playwright, and pnpm.

## Getting set up

Install pnpm, then you can either hit "Use this template" above or use degit:

```
npx degit phildenhoff/logseq-plugin-template my-ls-plugin
cd my-ls-plugin
git init
```

Then,

```
pnpm install
```


## Technical choices

### Why Svelte?

It's a pretty-good framework. Feel free to adapt this for any other framework.

### Why Vitest?

It's faster than Jest, and a better fit for unit tests than Playwright.

### Why Playwright?

It allows for component/integration-level tests in your plugin.

### Why pnpm?

It's faster than npm & yarn and more stable than bun...

