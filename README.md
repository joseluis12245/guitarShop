# Guitar Sales Web Management Developed with React + TypesScript + Vite

This app was made with react and the next structure:

- BootStrap was used to styled all the app, with a plain CSS file.
- Creation of functional components.
- Managing of props. 
- Using hooks such as useEffect, useMemo, useState.
- Custom hooks to manage the cart features.
- Using types, inheritance between interfaces.
- Configuration of local storage.
- TypeScript Implemented.

Published website: https://661dfcf95b6907864785da25--melodious-kangaroo-4b143b.netlify.app/

# Steps to running

- Please install nodeJS.
- run 'npm install'
- run 'npm run dev' and open the app in the browser.

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
