# cljsjs/feathers

Provides feathers

[](dependency)
```clojure
[cljsjs/feathers "2.3.0-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require [cljsjs.feathers]))
```

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies

## Maintenance

Bump the version number in build.boot.
