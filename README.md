# ✅ webpack 설정

`webpack.config.js` 파일 생성

## plugin 설명

1. `TerserWebpackPlugin`

- Javascript를 `최소화`
- console.log 제거, debugger 구문 제거등

2. `MiniCssExtractPlugin`

- CSS를 별도의 파일로 추출하여 JS파일별로 CSS파일을 생성

3. `css-loader`

`@import` `url()` `impoer/require`로 불러오는 css를 해석

# ✅babel 설정

## babel이란?

> ECMAScript 2015+ 이상의 코드를 이전 버전의 코드로 변환하는 도구

```js
npm i -D @babel/core @babel/preset-env @babel/cli
```

1. `@babel/core`

- 트랜스파일링 기능이 들어있음

2. `@babel/preset-env`

- 어떻게 변환해야할지 규칙인 플러그인을 모아놓은 세트
