# public-protos-js

This is dynamically generated JS package for BuyCoins Protocol Buffer stubs. Updates are automatically pushed via Circle CI to this repo when changes are merged into the main (private) buycoins-protos master branch.

## Installation & Usage
 ```
 "dependencies": {
    ...
    "public-protos-js": "git+https://github.com/buycoinsafrica/public-protos-js.git"
}
```

## Updating your protos-gem version
- Delete the public-protos-js folder from node_modules
- Delete the package-lock.json file or any other lockfile.
- Run npm install again.

As of now, we don't have version numbers/tags. All projects using public-protos-js should update to the latest commit as often as possible.
