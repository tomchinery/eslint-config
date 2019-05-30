# `@tomchinery/eslint-config`

> My personal [eslint](https://eslint.org/) config for hobby projects.

## Usage

**Install**

```bash
npm i @tomchinery/eslint-config
```

**Edit `.eslintrc.js`**:

```javascript
module.exports = {
    extends: ['@tomchinery/eslint-config']
}
```

**Edit `package.json`**:

```jsonc
{
    "scripts": {
        ...
        "lint": "eslint ./src/ --fix",
        ...
    }
}
```
