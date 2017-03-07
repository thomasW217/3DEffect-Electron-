# InteraxGUI Cross Platform Desktop application (Mac, Windows, Linux)

InteraxGUI desktop application with Electron.

### What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
InteraxGUI/dist
├── css/
│   ├── photon.css
│   ├── photon.min.css
├── fonts/
│   ├── photon-entypo.eot
│   ├── photon-entypo.svg
│   ├── photon-entypo.ttf
│   └── photon-entypo.woff
└── template-app/
    ├── js/
    │   └── menu.js
    ├── app.js
    ├── index.html
    └── package.json
```

We provide compiled CSS (`photon.*`), as well as the minified CSS. We also include the Entypo fonts and a template Electron application for you to quickly get started.

### Running documentation locally

1. If necessary, [install Jekyll](http://jekyllrb.com/docs/installation) (requires v2.5.x).
  * **Windows users:** Read [this unofficial guide](http://jekyll-windows.juthilo.com/) to get Jekyll up and running without problems.
2. Install the Ruby-based syntax highlighter, [Rouge](https://github.com/jneen/rouge), with `gem install rouge`.
3. From the root `/photon` directory, run `jekyll serve` in the command line.
4. Open <http://localhost:4000> in your browser, and boom!

Learn more about using Jekyll by reading its [documentation](http://jekyllrb.com/docs/home/).

## Development

1. Install node dependencies: `npm install`.
2. Open the example app: `npm start`.

Modifying source Sass files? Open a second Terminal tab and run `grunt` to kick off a build the compiled `photon.css`.
