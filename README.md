# create-xixu

## Scaffolding A Vite Project

> **Compatibility Note:**
> Vite requires [Node.js](https://nodejs.org/en/) version 14.18+, 16+. However, some templates require a higher Node.js version to work, please upgrade if your package manager warns about it.

With NPM:

```bash
$ npm create xixu@latest
```

With Yarn:

```bash
$ yarn create xixu
```

With PNPM:

```bash
$ pnpm create xixu
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite + Vue project, run:

```bash
# npm 6.x
npm create xixu@latest my-vue-app --template vue

# npm 7+, extra double-dash is needed:
npm create xixu@latest my-vue-app -- --template vue

# yarn
yarn create xixu my-vue-app --template vue

# pnpm
pnpm create xixu my-vue-app --template vue
```

Currently supported template presets include:

- `vue`
- `vue-ts`

You can use `.` for the project name to scaffold in the current directory.

```bash
npx degit user/project my-project
cd my-project

npm install
npm run dev
```

If the project uses `main` as the default branch, suffix the project repo with `#main`

```bash
npx degit user/project#main my-project
```
