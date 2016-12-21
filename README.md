# fortrabbit error pages

the latest and greatest fortrabbit custom error pages. feel free to use.

## Install

* check if you have installed all node modules defined in `package.json` via `npm install`

## Generate

* `node_modules/.bin/metalsmith` < generate a new `_site` folder

## Deploy

* Git subtree `gh_pages` is the generated folder `_site` > `git subtree push --prefix _site origin gh-pages`
