# Atom Flight Manual

This is the Atom book. Everything you need to know in order to use and hack Atom is in this Flight Manual.

You can find this book online at: http://atom.io/docs/latest/

This book is open source under a Creative Commons license.

[![atom-cover](https://cloud.githubusercontent.com/assets/378023/8718108/54c10686-2bdc-11e5-8d26-f7f807d63171.png)](https://github.com/atom/docs/releases/latest)

## License

This book is published under the Creative Commons BY-SA license. If you contribute to the work, you will have to agree to allow your content to be published under the self same license. Check out [the license file](LICENSE.asc) for more details.

## Current Progress

To check the current progress and planned content of the book, check out the [outline](outline.md). This is a good place to start if you're looking for something to add.

## Generating the book

### Prerequisites

* You'll need Ruby installed on your system. The required version can be found in *.ruby-version*.
* You'll need the `bundle` command installed. You can do this with `gem install bundler`.
* You'll need Node and NPM installed, too. The required version can be found in *package.json*.

### Fetching dependencies

You can always fetch the latest dependencies by opening the command line and running `script/bootstrap`:

``` sh
$ script/bootstrap
```

### Starting the site

You can start the site with `script/server`:

``` sh
$ script/server
Loading site data...
Compiling site...
…

Site compiled in 5.81s.
```

While the server is running, you can see the site in your browser at http://localhost:4000.

## Contributing

If you'd like to help out by making a change, adding content or improving something, take a look at the [contributor's guide](CONTRIBUTING.md).

## Maintainers

There is currently no one maintaining the book. Active contributions are welcome!
