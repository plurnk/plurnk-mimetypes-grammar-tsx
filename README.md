# @plurnk/plurnk-mimetypes-grammar-tsx

Pre-built `tree-sitter-tsx` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-tsx
```

## what's in here

- **`tsx.wasm`** — pre-built from the pinned upstream [tree-sitter-tsx](https://github.com/tree-sitter/tree-sitter-typescript) commit (`tsx` subdirectory) (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `tsx.wasm` is built from the upstream tree-sitter-tsx grammar; see the pinned commit for that project's attribution.
