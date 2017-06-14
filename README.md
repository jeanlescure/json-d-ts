# JSON d.ts

JSON definition for Typescript that allows loading `.json` files using `import`.

# Usage

In order to load a `.json` file using Typescript, do the following:

- Install this package

```
npm install --save-dev json-d-ts
```

- Add to your `tsconfig.json` the path to the installed module:

```
    "typeRoots": [
      "../node_modules/json-d-ts"
    ]
```

- Load your `.json` files easily using `import` statements:

```
import * as data from './example.json';
```