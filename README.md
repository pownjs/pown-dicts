[![Follow on Twitter](https://img.shields.io/twitter/follow/pownjs.svg?logo=twitter)](https://twitter.com/pownjs)

# Pown Dicts

Pown Dicts is a collection of various types of dictionaries.

## Quickstart

If installed globally as part of [Pown.js](https://github.com/pownjs/pown) invoke like this:

```sh
$ pown dicts
```

Otherwise install this module from the root of your project:

```sh
$ npm install @pown/dicts --save
```

Once done, invoke pown dicts like this:

```sh
$ ./node_modules/.bin/pown-cli dicts
```

## Usage

```
pown dicts [options] <search>

Assorted Dictionaries

Options:
  --version       Show version number                                  [boolean]
  --modules, -m   Load modules                                          [string]
  --help          Show help                                            [boolean]
  --download, -d  Download found dictionaries         [boolean] [default: false]
  --regex, -r     Search with regex                   [boolean] [default: false]
```

## Improvements

This is a great start but there are a number of things that the original author would like to improve. In no particular order here is the current wish list:

* Ability to transform/cleanup the file output
* Download progress bar - this could be another module providing this feature
