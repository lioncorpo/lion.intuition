[![Build Status](https://travis-ci.org/Krinkle/intuition.svg?branch=master)](https://travis-ci.org/Krinkle/intuition)

# Intuition

## Usage

To use it in a tool, read the  [Usage documentation](https://github.com/Krinkle/intuition/wiki/Documentation#usage).

## Quick start

```bash
git clone --recursive https://github.com/Krinkle/intuition.git
```

## Getting involved

### Testing

Use [Composer](https://getcomposer.org) for managing dependenices (such as [PHPUnit](http://www.phpunit.de)). Install Composer via your preferred package manager, or from [source](https://getcomposer.org/download/).

Prior to runnig tests, ensure presence of local dev dependencies:
```
composer install
```

Run the tests:
```
./tests/run
```

A small amount of frontend code is integrated via [Grunt](http://gruntjs.com/) on [node.js](http://nodejs.org/). Install the Grunt command-line utility:
`npm install -g grunt-cli`

Prior to runnig tests, ensure presence of local dev dependencies:
```
npm install
```

Run the tests:
```
npm test
```

### Misc

To regenerate the `AUTHORS.txt`:
```
npm install && grunt authors
```
