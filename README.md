# Configurations for elm-review

Here are a few configurations that you can use to get started with [`elm-review`](https://package.elm-lang.org/packages/jfmengels/elm-review/latest/).

These are only meant to be starting points. Feel free to add or remove rules as you please.

Note that all these are subjective to my own personal tastes and beliefs. I highly recommend reading the section *[When to enable a rule](https://package.elm-lang.org/packages/jfmengels/elm-review/latest/#when-to-write-or-enable-a-rule)* to decide to keep or add new rules.

The following configurations are available:

### For an Elm application

```bash
elm-review init --template jfmengels/elm-review-config/application
```

### For an Elm package

```bash
elm-review init --template jfmengels/elm-review-config/package
```

### For an `elm-review` package

Note that you already get this when running `elm-review new-package`, which I **highly** recommend because you get even more useful tools for free.

```bash
elm-review init --template jfmengels/node-elm-review/new-package/review-config-templates/2.3.0
```
