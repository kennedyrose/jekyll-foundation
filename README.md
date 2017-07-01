# Jekyll Foundation Netlify

Quickstart your Jekyll (v3) project with Zurb Foundation for Sites (v6, sass) and Netlify CMS.

## Getting Started

1. Install [Ruby and Ruby Gems](https://rvm.io/rvm/install)
1. Install [Jekyll](http://jekyllrb.com/) with: `gem install jekyll`
1. Install [Bundler](http://bundler.io/) with: `gem install bundler`
1. Install [Node.js](https://nodejs.org/en/)
1. Install [Yarn](https://yarnpkg.com/en/) with: `npm install --global yarn`

You only need to do these instructions once per machine.

## Installation

```bash
$ # Clone this repository
$ git clone https://github.com/kennedyrose/jekyll-foundation-netlify your-project-name

$ # Then navigate to the project directory
$ cd your-project-name

$ # Install all dependencies for the project
$ yarn
```

You only need to do this once after cloning the repository.

## Development

Start development on your local machine with: `yarn dev`.

You can stop the development task by pressing <kbd>ctrl</kbd>+<kbd>c</kbd> in the terminal.

## Useful File Locations

### HTML
- `_layouts/index.html`: The template used for the home page.
- `_layouts/page.html`: The template used for all pages.
- `_layouts/post.html`: The template used for all blog posts.
- `_includes/head.html`: This content will be placed at the top of every page. Includes the `<head />` content
- `_includes/footer.html`: This content will be placed at the bottom of every page.

You can also create additional layouts for other page types you create in the `_layouts` directory.

### Sass

The main Sass file is located in `assets/scss/app.scss`. The other directories in `assets/scss/` optionally show you how you can keep your Sass files seperated for more managable code.

If you do create a new Sass file, make sure to import it in the `app.scss` file or it will not get transpiled into CSS and therefore not exist on the site.

### Images

### Foundation Settings

[Getting started](https://github.com/core77/jekyll-foundation/wiki/Getting-started)
