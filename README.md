# bulma-webpack

> Bulma Customization with Webpack Bundler

## Goals

* Customize Bulma
* Optimize bundle size
* Implement critical path styling

## Command History

```bash
mkdir bulma-webpack
cd $_
echo "# bulma-webpack" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:m99coder/bulma-webpack.git
git push -u origin master
```

```bash
echo "node_modules" > .gitignore
npm init -y
npm install bulma --save
```

```bash
npm install webpack webpack-cli --save-dev
npm install css-loader sass-loader node-sass mini-css-extract-plugin --save-dev
```
