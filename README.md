<div align=center>

<picture>
  <source srcset="public/logo.webp">
  <img width='100px' alt="logo">
</picture>

# Next.js Starter Template

### A Minimal Next.js Starter Template.

</div>

## Features

- ⚡ **[Next.js](https://nextjs.org/)** - A React Framework for Production
- 🔥 **[App Router](https://nextjs.org/docs/app)** - It is a new paradigm for building applications using React's latest features.
- 🎨 **[Tailwind CSS](https://tailwindcss.com/)** - A Utility-First CSS Framework for Rapid UI Development
- 📦 **[TypeScript](https://www.typescriptlang.org/)** - A typed superset of JavaScript that compiles to plain JavaScript
- 📝 **[Biome](https://biomejs.dev/)** - One toolchain for your web project
- 🐶 **[Husky](https://typicode.github.io/husky/#/)** - A tool that makes Git hooks easy
- 🚫 **[lint-staged](https://github.com/okonet/lint-staged)** - Run linters against staged git files
- 📄 **[commitlint](https://commitlint.js.org/#/)** - Lint commit messages
- 🌐 **[next-intl](https://next-intl-docs.vercel.app/)** with(shared pathname strategy) - Internationalization for Next.js

Under Construction 🚧
- 🛡️ **[auth.js](https://next-intl-docs.vercel.app/)** (with Credentials) - Authentication for the Web.


## Getting Started

```bash
bun create next-app -e "https://github.com/yusuf-saydullayev/nextjs-starter-template" <project-name>

npx create-next-app -e "https://github.com/yusuf-saydullayev/nextjs-starter-template" <project-name>
```

**Install dependencies**

```bash
bun i || pnpm i || yarn || npm i
```

## Available Scripts

In the project directory, you can run:

| **Script**   | **Description**                                      |
| ------------ | ---------------------------------------------------- |
| `dev`        | Runs the app in the development mode.                |
| `build`      | Builds the app for production to the `.next` folder. |
| `start`      | Runs the built app in the production mode.           |
| `lint`       | Runs biome lint on the project.                       |
| `type-check` | Runs TypeScript type checker.                        |
| `fmt`        | Formats the code with Biome.                      |
| `fmt:check`  | Checks if the code is formatted with Biome.       |
| `prepare`    | Installs husky git hooks.                            |

## After Installation Checklist

- [ ] Update `package.json` with your project details.
- [ ] Update `README.md` with your project details.
- [ ] Update `LICENSE` with your name and year.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
