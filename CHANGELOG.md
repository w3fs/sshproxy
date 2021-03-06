# Change Log

All notable changes to this project will be documented in this file
automatically by Versionist. DO NOT EDIT THIS FILE MANUALLY!
This project adheres to [Semantic Versioning](http://semver.org/).

## v1.4.3 - 2018-02-02

* Remove excessively verbose logging #32 [Will Boyce]
* Wait until all channels/requests have been serviced before closing connection #32 [Alexis Svinartchouk]

## v1.4.2 - 2017-11-30

* Use keyType during key generation to create correct key type #28 [Andreas Fitzek]

## v1.4.1 - 2017-07-11

* Expose version information to build and add --version flag [Will Boyce]

## v1.4.0 - 2017-07-10

* Add support for running shell with alternative credentials [Will Boyce]

## v1.3.0 - 2017-06-20

* Reflect command exit status in 'exit-status' request [Will Boyce]
* Kill running command if requesting channel dies [Will Boyce]
* Improve error handling [Will Boyce]
* Improve pseudo-terminal handling [Will Boyce]

## v1.2.1 - 2017-06-07

* Remove debug code from Makefile [Will Boyce]

## v1.2.0 - 2017-06-07

* Update README [Will Boyce]
* Update Makefile and add circleci config [Will Boyce]
* Lint fixes [Will Boyce]
* Do not pass env vars from client to shell by default [Will Boyce]

## v1.1.2 - 2017-05-18

* Also use ecdsa and dsa host keys [Will Boyce]

## v1.1.1 - 2017-05-17

* Fix issue where sshproxy would fail to start if no banner was specified [Will Boyce]
* Rename ambiguous "unauth" config variable to "auth-failed-banner" [Will Boyce]
* Add configuration option for setting MaxAuthTries [Will Boyce]

## v1.1.0 - 2017-05-15

* Add support for displaying a banner to user after failed authentication [Will Boyce]

## v1.0.0 - 2017-04-13

* Initial release [Will Boyce]
