boilerplate isomorphic jspm typescript

# Requirements/Recommended

 - [node] `v4+`
 - [atom]
    - Packages
      - [atom-typescript]
      - [atom-lint]
      - [linter-tslint]

# Quick start

```bash
# first time
npm install -g gulp tsd jspm jspm-server typescript babel-cli
npm install

# every time
jspm-server
gulp watch

# when modifying gulp tasks
node ./npm-scripts/watch-gulp-tasks.js
```

# Features

 - [typescript] - javascript type support
 - [jspm] - package manager, browser module loader, bundler
 - [gulp] - automated build system

---

[node]: https://nodejs.org/
[atom]: https://atom.io/
[atom-typescript]: https://atom.io/packages/atom-typescript
[gulp]: http://gulpjs.com/
[typescript]: http://www.typescriptlang.org/
[backbone]: http://backbonejs.org/
[tsd]: http://definitelytyped.org/tsd/
[tslint]: http://palantir.github.io/tslint/
[atom-lint]: https://atom.io/packages/atom-lint
[linter-tslint]: https://atom.io/packages/linter-tslint
[es5-shim]: https://github.com/es-shims/es5-shim
[jspm]: http://jspm.io/
