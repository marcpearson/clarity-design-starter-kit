# Clarity Design Starter Kit

It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript module bundling with webpack
  - Image compression

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (Version 10 or greater recommended)
- [Git](https://git-scm.com/)
- [Yarn](https://yarnpkg.com/)

### Manual Setup

To manually set up the starter kit, first download it with Git:

```bash
git clone https://github.com/marcpearson/clarity-design-starter-kit projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
yarn
```

Finally, run `yarn start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8080
```

To create compressed, production-ready assets, run `yarn build`.
