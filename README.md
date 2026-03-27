# @nacal-tools/configs

Shared configuration packages for development tools.

## Packages

### [@nacal-tools/biome-config](./packages/biome-config)

Shared [Biome](https://biomejs.dev/) configuration.

#### Install

```bash
npm install -D @nacal-tools/biome-config
```

#### Usage

Create a `biome.json` in your project root:

```json
{
  "extends": ["@nacal-tools/biome-config/biome.json"]
}
```

#### Rules

- **Formatter**: spaces (indent width: 2), line width 80
- **JavaScript**: double quotes, no semicolons, no trailing commas, arrow parens as needed
- **Linter**: recommended rules + `noConsole`, `noSecrets`, `noBarrelFile`
- **Assist**: auto organize imports

## License

[MIT](./LICENSE)
