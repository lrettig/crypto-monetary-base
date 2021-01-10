# Crypto Monetary Base

Expected cryptocurrency supply distributions.

See [agalea91/crypto-monetary-base](https://github.com/agalea91/crypto-monetary-base) for background info.

## Environment

You should have no issue installing and running jupyter, but if you wish to regenerate the notebooks/graphs you may encounter compatibility issues with different environments. The following environment is recommended:

- Python 3.8
- Node 14

Install these packages using `apt` as they are required by the `canvas` npm package that's used to generate the graphs:

`sudo apt-get install build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev libpixman-1-dev libjpeg62-turbo-dev`

## Running

First, run `npm install`. Then use `pipenv`:

```
pipenv install
pipenv shell
jupyter lab
```
