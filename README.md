# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) only for my projects

## Install

```sh
pnpm add --save-dev @Sevteen/tsconfig
```

*This config requires TypeScript 5.5 or later.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@sindresorhus/tsconfig"
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@sindresorhus/tsconfig",
	"compilerOptions": {
		"target": "ES2023"
	}
}
```
