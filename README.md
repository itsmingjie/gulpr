Mingjie's Starter Environment
---

What's set up here:

- Sass (LibSass)
- Autoprefixer
- CSS Minification
- JSHint
- Scss Lint (based on [this](https://github.com/causes/scss-lint/blob/master/config/default.yml) config)
- HTML Minification
- BrowserSync
- Image Minification
- GH-Pages deployment from dist/ folder

## To Get Started:

1. `git clone` & `cd`
1. Run `rm -rf .git` to remove the Git file from the repo and `git init` for a clean history
1. `npm install` to download dependancies
1. In the terminal, enter `gulp` to make everything run
1. Files will be generated from the `dist/` folder
1. For Netlify, use build command `gulp build`
1. To wipe the `dist/` folder, use `gulp clean`