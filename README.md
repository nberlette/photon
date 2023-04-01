# [Photon](https://photon.berlette.com)

UI toolkit for building desktop apps with Electron.

## Getting started

### Clone the repo

```sh
git clone https://github.com/nberlette/photon.git
```

### [Read the docs](https://photon.berlette.com)

Learn about the components, how to get your new application started, and using the included fonts.

> **Note**: the `master` branch is the active, unstable development branch. Breaking changes can be expected without prior notice. If you're looking to download a stable copy of the repo, check the [tagged downloads](https://github.com/nberlette/photon/tags).

## What's included

Within the download you'll find the following directories and files, logically grouping common assets. You'll see something like this:

```
photon/
├── css/
│   ├── photon.css
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

We provide compiled CSS (`photon.*`). We also include the Entypo fonts and a template Electron application for you to quickly get started.

## Documentation

Photon's documentation is built with [Jekyll](http://jekyllrb.com) and publicly hosted on GitHub Pages at [photon.berlette.com](https://photon.berlette.com). The docs may also be run locally.

### Running documentation locally

1. If necessary, [install Jekyll](http://jekyllrb.com/docs/installation) (requires v2.5.x).
  * **Windows users:** Read [this unofficial guide](http://jekyll-windows.juthilo.com/) to get Jekyll up and running without problems.
2. Install the Ruby-based syntax highlighter, [Rouge](https://github.com/jneen/rouge), with `gem install rouge`.
3. From the root `/photon` directory, run `jekyll serve` in the command line.
4. Open [`localhost:4000`](http://localhost:4000) in your browser, and boom!

Learn more about using Jekyll by reading its [**documentation**](http://jekyllrb.com/docs/home/).

## Contributing

Please file a GitHub issue to [**report a bug**](https://github.com/nberlette/photon/issues). When reporting a bug, be sure to follow the [**contributor guidelines**](https://github.com/nberlette/photon/blob/master/.github/CONTRIBUTING.md).


### Commits

Please try to follow the Conventional Commits v1.0.0 standard. The [**full specification can be found here**](https://www.conventionalcommits.org/en/v1.0.0/).

### Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Photon is maintained under the Semantic Versioning guidelines. Sometimes we screw up, but we'll adhere to these rules whenever possible.

Releases will be numbered with the following format:

**`<major>.<minor>.<patch>`**

And constructed with the following guidelines:

* Breaking backward compatibility **bumps the major** while resetting minor and patch
* New additions without breaking backward compatibility **bumps the minor** while resetting the patch
* Bug fixes and misc changes **bumps only the patch**

For more information on SemVer, please visit [**semver.org**](http://semver.org).

## Development

1. Install node dependencies: `npm install`.
2. Open the example app: `npm start`.

Modifying source Sass files? Open a second Terminal tab and run `npm run build` to kick off a build of the compiled `photon.css`.

## Maintainers

Nicholas Berlette
* https://github.com/nberlette
* https://berlette.com

Connor Sears
* https://twitter.com/connors
* https://github.com/connors

## License

MIT © Connor Sears and Nicholas Berlette. All rights reserved.
