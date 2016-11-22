# package-store-spec

## Store directory structure

Path structure: `<package source>/<package id>`

### Packages from npm registry

`<registry URL>/<package name>/<package version>`

E.g.: `registry.npmjs.org/gulp/2.1.0`

### Packages from git

`<git URL domain>/<git path>/<commit hash>`

E.g.: `github.com/alexGugel/ied/b246270b53e43f1dc469df0c9b9ce19bb881e932`

### Tarballs

`<domain>/<path to tarball>`

E.g.: `registry.npmjs.org/is-array/-/is-array-1.0.1`
