# eslint-config-base
Base configurations for ESLint

## Usage
To install package, run:

```
npm install --save-dev @afsv/eslint-base-config
```

To use this config, create .eslintrc.json in the project root and add these lines there:
```
{
  "extends": "@afsv/eslint-base-config"
}
```
## Use Prettier for formatting
This config disables all formatting rules. It assumes you will use Prettier to format your code.

## Don't ignore warnings
Warnings and errors have same meaning in this config. You should not ignore warnings in your CI pipelines.
Some of the rules are flagged as warnings just to enable you to write and debug code without covering the entire screen with red marks.
You must fix all warnings before commit.
