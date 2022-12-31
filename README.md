## Requirements

- Typescript >= 4.5.x
- node >= 16.x
- pnpm

## Install


Any package manager should do the trick but i recommend using [Pnpm](https://pnpm.io).

```bash
pnpm i
```

## Start

*You must create a `<NODE_ENV>.js` file for each env at the root of your project.*

The structure of the env file can be found in the configuration service.

### Dev

```bash
pnpm start:dev
```

### Test

```bash
pnpm start:test
```

### Production

You need to transpile the Typescript because executing the command.

```bash
pnpm tsc && pnpm start:production
```

## Tests & Lint

```bash
pnpm test
```

```bash
pnpm lint
```

