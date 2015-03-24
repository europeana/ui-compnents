# europeana ui-components
europeana ui-components package. automatically updated via a [jenkins](http://jenkins.eanadev.org/job/ui-components-develop/) build script when a commit is made against the [Europeana Pattern Lab](https://github.com/europeana/Europeana-Patternlab) repo.

## installation
### php
add the following to your project `composer.json` file. alter the require statement depending on the branch you want to use: `dev-develop` for the develop branch, or `dev-master` for the master branch.

```javascript
"repositories": [
  {
    "type": "vcs",
    "url": "https://github.com/europeana/ui-components"
  }
],
"require": {
  "europeana/ui-components": "dev-develop"
}
```
