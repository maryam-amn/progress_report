# Progress report

**Version 2.0.2 : [Changelog](./CHANGELOG.md)** <!-- x-release-please-version -->

> This repo is a template repository to create your own progress report in Markdown.
> The Markdown will be compiled into a static website using [Astro stralight template](https://github.com/withastro/starlight).
> Creating a progress report is a **requirement** for the CFC of computer scientist applications development in Switzerland.

## How to use

1. Create a new repository using this template repository (click on the green button "Use this template").
2. Clone your new repository on your machine.
3. In the `astro.config.mjs` file, edit all lines with a `TODO` comment to your corresponding information.
4. Install dependencies and run the dev server :
    ```bash
    pnpm install
    pnpm dev
    ```
5. Then you can make more changes to the Markdown content and see the result in your browser. Don’t forget to check [Starlight md docs](https://starlight.astro.build/guides/authoring-content/).

## How to add content

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Images can be added to `src/assets/` and embedded in Markdown with a **relative link**.

Static assets, like favicons, can be placed in the `public/` directory.

Static assets and links to pages must include the site base path to work. Astro builder does not automatically inclute it.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

