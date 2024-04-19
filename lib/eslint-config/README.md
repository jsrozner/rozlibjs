# @rozlib/eslint-config
https://github.com/exbotanical/eslint-config

Extensible eslint configurations for the punctilious developer.

## Packages

- `all` Aggregate of Vue, React, and Typescript-specific rulesets.
- `base` Base configuration with rulesets for markdown, yaml, json, package.json, and code.
- `javascript` Extension of `base` for JavaScript codebases.
- `react` React TypeScript rulesets. Additionally includes Cypress and accessibility rulesets.
- `typescript` TypeScript rulesets.
- `vue` Vue TypeScript rulesets. Additionally includes Cypress and accessibility rulesets.

## Usage

In .eslintrc,

```json
{
  "extends": ["@rozlib"]
}
```

Base

```bash
pnpm add -D @rozlib/eslint-config-base
```

```json
{
  "extends": ["@rozlib/base"]
}
```

Javascript

```bash
pnpm add -D @rozlib/eslint-config-javascript
```

```json
{
  "extends": ["@rozlib/javascript"]
}
```

React

```bash
pnpm add -D @rozlib/eslint-config-react
```

```json
{
  "extends": ["@rozlib/react"]
}
```

TypeScript

```bash
pnpm add -D @rozlib/eslint-config-typescript
```

```json
{
  "extends": ["@rozlib/typescript"]
}
```

Vue

```bash
pnpm add -D @rozlib/eslint-config-vue
```

```json
{
  "extends": ["@rozlib/vue"]
}
```
