# eslint-plugin-svelte-runes-bug

Having `compilerOptions` in the Svelte config leads to a `eslint` error, saying all runes are undefined.

(Weirdly this does not occur when the variable is named like the rune, see `+page.svelte`)

## Important files

- `svelte.config.js`
- `src/routes/+page.svelte`
