### `@atos6/tsconfig`

Gloabal company tsconfig

- <https://www.typescriptlang.org/docs/handbook/tsconfig-json.html>
- <https://www.typescriptlang.org/docs/handbook/compiler-options.html>
- <https://github.com/tsconfig/bases>
- <https://deno.land/manual/getting_started/typescript#custom-typescript-compiler-options>
- <https://github.com/sindresorhus/tsconfig>

Add the package to your `"devDependencies"`:

```sh
yarn add --dev @atos6/tsconfig
```

Add to your `tsconfig.json`:

```json
"extends": "@atos6/tsconfig/tsconfig.json"
```

Only Strict Rules:

```json
"extends": "@atos6/tsconfig/strict.json"
```

Create React App:

```json
"extends": "@atos6/tsconfig/react.json"
```

[Node 12](https://github.com/tsconfig/bases/blob/master/bases/node12.json):

```json
"extends": "@atos6/tsconfig/node12.json"
```
