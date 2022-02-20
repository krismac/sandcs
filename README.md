# ReadMe

This is a small business template built with [Victor Hugo](https://github.com/netlify/victor-hugo) and [Netlify CMS](https://github.com/netlify/netlify-cms).

## Updating the website

Use our deploy button to get your own copy of the repository.

This will setup everything needed for running the CMS:

* A new repository in your GitHub account with the code [![Github Page]](https://github.com/krismac/sandcs/)
* Full Continuous Deployment to Netlify's global CDN network
* Control users and access with Netlify Identity
* Manage content with Netlify CMS [![CMS Admin Page]](http://www.sandcs.ie/admin)

## Local Development

Clone this repository, and run `yarn` or `npm install` from the new folder to install all required dependencies.

Then start the development server with `yarn start` or `npm start`.

## Layouts

The template is based on small, content-agnostic partials that can be mixed and matched. The pre-built pages showcase just a few of the possible combinations. Refer to the `site/layouts/partials` folder for all available partials.

## CSS

The template uses a custom fork of Tachyons and PostCSS with cssnext and cssnano. Customize the template, refer to `src/css/imports/_variables.css` where most of the important global variables like colors and spacing are stored.
