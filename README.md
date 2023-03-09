
# mlz-prettier-config

prettier 统一规范配置

## Installation

`npm i -D @mlz/prettier-config`

## Usage

#### 在项目根目录新建 `.prettierrc.json` 文件，并写入下面👇代码

```json
"@mlz/prettier-config"
```

#### 如需覆盖部分配置，在项目根目录新建 `.prettierrc.js` 文件，并写入下面👇代码

```js
module.exports = {
  ...require('@mlz/prettier-config'),
  semi: true,
}
```
