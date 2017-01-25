# gendo

Generates docs via [documentationjs](http://documentation.js.org/), updates README checks that in and then generates
github pages with nicely rendered docs.

![assets/gendo.gif](assets/gendo.gif)

```
# let documentationjs find the files to document
gendo

# specify the files to generate docs for
gendo file1.js lib/file2.js
```

## Requirements

- a `README.md` with an API section, i.e. `## API`
- a `gh-pages` branch, if not found it is generated for you

## Installation

    npm install gendo

## Docs generated with gendo

### ah-collector 

- [readme](https://github.com/thlorenz/ah-collector)
- [gh-pages](https://thlorenz.github.io/ah-collector)

## License

MIT
