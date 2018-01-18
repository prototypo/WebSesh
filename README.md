# WebSesh TinyMCE Plugin

WebSesh is a TinyMCE editor plugin to facilitate writing ancient Egyptian hieroglyphs in HTML.

WebSesh is intended to provide complete support for both “verbalist” writing using categorised signs, a full picklist in Manuel de Codage (MdC) style, and direct entry of Gardiner numbers. The project is currently a long way from having a complete feature set.

Please contribute! The project needs translators, software developers, Egyptologists, and technical writers.

## The development server

By running the `npm start` command you start the development server and open a browser window with an instance of TinyMCE with your plugin added to it. This window will reload automatically whenever a change is detected in the `index.html` file in the `static` folder or in one of the JavaScript files in the `src` directory.

## The production build

By running the `npm run build` command Webpack will create a `dist` directory with a child directory with the name of your plugin (websesh) containing three files:

* `plugin.js` - the bundled plugin
* `plugin.min.js` - the bundles, uglified and minified plugin
* `LICENSE` - a file explaining the license of your plugin (copied over from `src/LICENSE`) 
