# Ember-cli-surge
[![Build Status](https://travis-ci.org/kiwiupover/ember-cli-surge.svg)](https://travis-ci.org/kiwiupover/ember-cli-surge)
[![Ember Observer Score](http://emberobserver.com/badges/ember-cli-surge.svg)](http://emberobserver.com/addons/ember-cli-surge)

## Static Web Publishing for Front-End Developers
[surge.sh](http://surge.sh) Zero-bullshit, single–command,
bring your own source control web publishing CDN. Yes, it's free.
[Surge Docs](http://surge.sh/help)


## Installation

From within your Ember CLI application run:

For ember-cli >= 0.2.3, run:

```sh
ember install ember-cli-surge
```

Otherwise, for ember-cli 0.1.5 - 0.2.3, run:

```sh
ember install:addon  ember-cli-surge
```

## Deploy

```sh
ember surge
```

This command will build your ember app using the production environment.
Then deploy that code from your `dist` folder
to the url `<your-project-name>.surge.sh`

## Updating the Domain Name

The domain name that your project builds can update in the `CNAME` file.
Make sure your domain is `<something>.surge.sh`.
For more info look at the [Surge Docs](http://surge.sh/help/remembering-a-domain)


## Contributing

### Running Tests

* `npm test`

## License

MIT
