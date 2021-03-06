[![Build Status](https://travis-ci.org/thesuperhomie/job-search.svg?branch=master)](https://travis-ci.org/thesuperhomie/job-search)

# job-search

A CLI for searching jobs. Follow the prompt to find your next new gig! This CLI takes advatange of `pupeteer` to automate loading up your next job search.

![Example](.github/job-search-example.gif)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Make sure that you have Node 8.x or later installed. See instructions [here](https://nodejs.org/en/download/).

### Installing

1. Install job-search globally so you can use the CLI anywhere with a command line
* `$ npm i -g job-search`
* *If you're having permission issues creating a Chromium directory try*: `$ sudo npm install -g job-search --unsafe-perm=true --allow-root`
2. Start using job-search
* `$ job-search`

## Running the tests

`$ npm run test`

## Built With

* [Pupeteer](https://www.npmjs.com/package/puppeteer) - Chrome or Chromium over the DevTools Protocol
* [Commander](https://www.npmjs.com/package/commander) - command-line interfaces
* [Inquirer](https://www.npmjs.com/package/inquirer) - command line user interfaces

## Contributing

Please read [CONTRIBUTING.md](https://github.com/thesuperhomie/job-search/blob/master/.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/thesuperhomie/job-search/tags). 

## Authors

* **Claudio Herrera** - *Creator and active maintainer* - [thesuperhomie](https://github.com/thesuperhomie)

### Special Thanks
[PurpleBooth](https://gist.github.com/PurpleBooth) - Great contributing template!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.