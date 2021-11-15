# Arpan KC Portfolio website
[![Netlify Status](https://api.netlify.com/api/v1/badges/b3d729b4-2a57-42b1-bc58-301d113ab516/deploy-status)](https://app.netlify.com/sites/adoring-babbage-b2fad8/deploys)


A simple portfolio website with a Continuous Deployement pipeline setup using Github actions.

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

After installation, run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You must have npm installed globally in order to use this build environment.
