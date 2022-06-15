# ⚛️ React, TypeScript, Vite Boilerplate

This is a boilerplate to be used as a starter for using React with
[TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/),
linting and formatting.

## 🎨 Linting and formatting

**ESLint** is used with:
- [`typescript-eslint`](https://github.com/typescript-eslint/typescript-eslint)
- [`eslint-plugin-react`](https://github.com/jsx-eslint/eslint-plugin-react)
- [`eslint-plugin-import`](https://github.com/import-js/eslint-plugin-import) with TypeScript resolver
- [`eslint-plugin-prettier`](https://github.com/prettier/eslint-plugin-prettier)
- [`eslint-config-prettier`](https://github.com/prettier/eslint-config-prettier)

As the Prettier *plugin* is used, it is run as an ESLint rule for both linting
and formatting.

## 🔧 Development Server

Run `npm run dev` to start the Vite development server.

## Building

For the production builds, **Vite** is also used.

Run `npm run build` to create a build in the `dist` folder.

