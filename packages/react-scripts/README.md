## 用法

`npx create-react-app YOUR_PROJECT_NAME --scripts-version simplified-react-scripts`

## environment

因为用到husky，所以要求：
- Node >= 10
- Git >= 2.13.0

refer:
- [husky](https://github.com/typicode/husky)
- [prettier](https://prettier.io/docs/en/precommit.html)

## features

### pre-commit hook for prettier

git commit前会自动用prettier format

尽管如此，还是推荐使用vscode时安装Prettier插件，并在settings里设置format on save为true