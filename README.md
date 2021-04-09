# Silverstripe security recipe

A recipe for adding various security-focused modules to a Silverstripe website.

## In this recipe 

### Authentication boilerplate

+ The [nswdpc/silverstripe-authentication-boilerplate](https://github.com/nswdpc/silverstripe-authentication-boilerplate), providing:
  + Multi-factor Authentication (MFA) for the administration area via the [Silverstripe TOTP Authenticator](https://github.com/silverstripe/silverstripe-totp-authenticator)
  + [Pwned Password checks](nswdpc/silverstripe-pwnage-hinter) via the pwnedpasswords API provided by [Have I Been Pwned](https://haveibeenpwned.com)
  + [Breached account checks](nswdpc/silverstripe-pwnage-hinter) via the haveibeenpwned API provided by [Have I Been Pwned](https://haveibeenpwned.com)
  + The [Silverstripe security extensions module](https://github.com/silverstripe/silverstripe-security-extensions)
  + The [Silverstripe security report module](https://github.com/silverstripe/silverstripe-securityreport)

### Content Security Policy

+ The [NSWDPC CSP](https://github.com/nswdpc/silverstripe-csp) module

### Captcha

+ The [NSWDPC reCAPTCHA v3](https://github.com/nswdpc/silverstripe-recaptcha-v3) base module

### Useful extras

+ [silverstripe/login-forms](https://github.com/silverstripe/silverstripe-login-forms)
+ [silverstripe/mimevalidator](https://github.com/silverstripe/silverstripe-mimevalidator)

## Configuration

Per the Silverstripe recipe standard there is no configuration provided in this module. Its aim is to bring together a set of Silverstripe security modules to be used together in a standardised way. Default configuration settings can be found in recipe modules.

The authentication boilerplate module provides a standard set of rules for defining access to websites. You can modify these rules using the Silverstripe configuration API.

## Installation

The only supported way of installing this recipe is via [composer](https://getcomposer.org)

```
composer require-recipe nswdpc/silverstripe-security-recipe
```
### About recipes

See the [recipe plugin page](https://github.com/silverstripe/recipe-plugin) for information on how recipes work.

## LICENSE

[BSD-3-Clause](./LICENSE.md)

## Maintainers

+ [dpcdigital@NSWDPC:~$](https://dpc.nsw.gov.au)

## Bugtracker

We welcome bug reports, pull requests and feature requests on the Github Issue tracker for this project.

Please review the [code of conduct](./code-of-conduct.md) prior to opening a new issue.

## Security

If you have found a security issue with this module, please email digital[@]dpc.nsw.gov.au in the first instance, detailing your findings.

## Development and contribution

If you would like to make contributions to the module please ensure you raise a pull request and discuss with the module maintainers.

Please review the [code of conduct](./code-of-conduct.md) prior to completing a pull request.
