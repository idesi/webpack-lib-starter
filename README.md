# webpack-lib-starter
`webpack-lib-starter` can be used as a starting point when writing JavaScript libraries that follow the UMD pattern.

The starter supports the following out of the box:
* ES2015
* Testing using mocha & chai
* Travis CI
* Semantic Release
* Commitizen
* Ghooks

Files built by `Webpack` are output to the `lib` directory and `libraryName.min.js` will be the entry point.

To commit, simply add all changes and then run `npm run commit`

Tests are run on every commit.

When you push your commits to remote, a production build is done which minifies the code. `TravisCI` build also kicks in, and `semantic-release` will release a new version based on the commit messages.
