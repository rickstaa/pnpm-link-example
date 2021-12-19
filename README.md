# pnpm-link-example

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/pnpm-link-example.svg)](https://www.npmjs.com/package/pnpm-link-example) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

Small example on how to use [pnpm](https://pnpm.io/) linking to use a local library. Create with [create-react-library](https://github.com/transitive-bullshit/create-react-library).

## Pnpm link

The [pnpm](https://pnpm.io/) linking command is similar to the [npm link](https://docs.npmjs.com/cli/v8/commands/npm-link) command the only thing that has to be added is the `-g` flag. To use the `pnpm-link-example` package in the example package, you must first run the `pnpm link -g` command from the workspace folder. Then cd into the `example` directory and run the `pnpm link -g pnpm-link-example`.

## Pnpm peer dependency error

If you get a pnpm peer dependency error you have to run the `npm cache clean -f` command.

## License

MIT © [rickstaa](https://github.com/rickstaa)
