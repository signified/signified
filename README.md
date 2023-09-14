# Signified

The Signified website.

## Installation

```shell
git clone git@github.com:signified/signified.git
cd signified
```

## Usage

```shell
bundle exec jekyll serve
```

### With Docker

```shell
docker run -p 4000:4000 -v $(pwd):/home/jekyll -w /home/jekyll -it --entrypoint /bin/bash jekyll/jekyll:3
bundle
jekyll build
jekyll serve
```

## Contributing

See [Contributing](https://github.com/loriqeet/.github/blob/main/CONTRIBUTING.md).

## Credits

See [Contributors](https://github.com/signified/signified/graphs/contributors).
