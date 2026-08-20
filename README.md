# Micro Skeleton

![Micro Skeleton activity](https://heatbadger.now.sh/github/readme/contributte/micro-skeleton/)

<p align=center>
  <a href="https://github.com/contributte/micro-skeleton/actions"><img alt="Build status" src="https://badgen.net/github/checks/contributte/micro-skeleton/master"></a>
  <a href="https://codecov.io/gh/contributte/micro-skeleton"><img alt="Code coverage" src="https://badgen.net/codecov/c/github/contributte/micro-skeleton"></a>
  <a href="https://packagist.org/packages/contributte/micro-skeleton"><img alt="Packagist downloads" src="https://badgen.net/packagist/dm/contributte/micro-skeleton"></a>
  <a href="https://packagist.org/packages/contributte/micro-skeleton"><img alt="Packagist version" src="https://badgen.net/packagist/v/contributte/micro-skeleton"></a>
</p>
<p align=center>
  <a href="https://packagist.org/packages/contributte/micro-skeleton"><img alt="Supported PHP version" src="https://badgen.net/packagist/php/contributte/micro-skeleton"></a>
  <a href="https://github.com/contributte/micro-skeleton"><img alt="License" src="https://badgen.net/github/license/contributte/micro-skeleton"></a>
  <a href="https://bit.ly/ctteg"><img alt="Gitter support" src="https://badgen.net/badge/support/gitter/cyan"></a>
  <a href="https://bit.ly/cttfo"><img alt="Forum support" src="https://badgen.net/badge/support/forum/yellow"></a>
  <a href="https://contributte.org/partners.html"><img alt="Sponsor Contributte" src="https://badgen.net/badge/sponsor/donations/F96854"></a>
</p>

<p align=center>
Website 🚀 <a href="https://contributte.org">contributte.org</a> | Contact 👨🏻‍💻 <a href="https://f3l1x.io">f3l1x.io</a> | Twitter 🐦 <a href="https://twitter.com/contributte">@contributte</a>
</p>

<p align=center>
	<img alt="Micro Skeleton demo" src="https://api.microlink.io?url=https%3A%2F%2Fexamples.contributte.org%2Fmicro-skeleton%2F&overlay.browser=light&screenshot=true&meta=false&embed=screenshot.url"></img>
</p>

-----

## Goal

This is a small Nette starter kit for prototypes and simple websites.

## Demo

https://examples.contributte.org/micro-skeleton/

## Website quick start

You will need `PHP 8.4+` and [Composer](https://getcomposer.org/).

```bash
composer create-project -s dev contributte/micro-skeleton acme
cd acme
make setup
```

```bash
make dev
```

Open [http://localhost:8000](http://localhost:8000). The default route renders templates from `app/templates`; paths without a matching template render the bundled 404 page.

## Development commands

```bash
make cs       # coding standard only
make csf      # fix coding style
make clean    # remove temporary files and logs
```

The `phpstan`, `tests`, and `coverage` Make targets are placeholders in this skeleton; they do not run checks yet.

## Configuration

The skeleton's base configuration is in `config/config.neon`. Development mode is enabled by `make dev` through `NETTE_DEBUG=1` and `NETTE_ENV=dev`.

## Development

See [how to contribute](https://contributte.org/contributing.html) to this package.

This package is currently maintaining by these authors.

<a href="https://github.com/f3l1x">
    <img alt="Milan Šulc" width="80" height="80" src="https://avatars2.githubusercontent.com/u/538058?v=3&s=80">
</a>

-----

Consider to [support](https://contributte.org/partners.html) **contributte** development team.
Also thank you for using this project.
