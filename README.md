# JFFE-Development-Rules
九方技术前端开发规范

### `Eslint`

#### 标准化`eslint.config.js`

```javascript
/*eslint no-undef: "warn"*/
module.exports = {
  root: true,
  env: {
    node: true,
    browser: true,
  },
  extends: ['plugin:vue/essential', 'eslint:recommended'],
  parserOptions: {
    parser: 'babel-eslint',
  },
  rules: {
    'eqeqeq': ['error', 'smart'],
    'no-multi-spaces': ['error', { ignoreEOLComments: true }],
    'no-new-wrappers': 'error',
    'require-await': 'error',
    'no-duplicate-imports': ['error', { includeExports: true }],
    'no-use-before-define': 'warn',
    'no-undefined': 'warn',
    'array-bracket-spacing': ['warn', 'never'],
    'block-spacing': ['warn', 'never'],
    'eol-last': 'warn',
    'func-call-spacing': ['warn', 'never'],
    'implicit-arrow-linebreak': 'warn',
    'indent': ['error', 2],
    'key-spacing': 'warn',
    'lines-around-comment': 'warn',
    'no-lonely-if': 'error',
    'no-multiple-empty-lines': ['warn', { max: 1, maxBOF: 0, maxEOF: 0 }],
    'no-trailing-spaces': ['warn', { ignoreComments: true }],
    'no-whitespace-before-property': 'error',
    'quotes': ['error', 'single'],
    'semi': 'warn',
    'semi-spacing': 'warn',
    'semi-style': ['error', 'last'],
    'arrow-spacing': 'warn',
    'no-var': 'error',
    'prefer-const': 'warn',
    'prefer-destructuring': 'warn',
    'prefer-template': 'warn',
  },
};
```

#### 1. vue2 项目使用 `eslint`

#### 2. vue3 项目使用 `eslint`
