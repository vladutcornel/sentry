# Sentry

Sentry is a PHP 5.3+ fully-featured authentication & authorization system. It also provides additional features such as user groups and additional security features.

Sentry is a framework agnostic set of interfaces with default implementations, though you can substitute any implementations you see fit.

# 2.2 Changelog
The last official Sentry version is v2.1 and was intended to be used with Laravel 4.
This is a fork based on [feature/laravel-5](https://github.com/vladutcornel/sentry/tree/feature/laravel-5), intended to be used with Laravel 5 and the following changes:

1. Global throttling - Block an entire IP if too many consecutive attempts failed
2. Login throttling - Treat registered user and invalid user the same. This should prevent an attacker from knowing what logins are valid and can be attacked further.
3. Keep adding login attempts after suspended
4. Improve support for Laravel5, if needed
5. (Not implemented) Drop support for FuelPHP
6. (Not implemented) Drop support for CodeIgniter

### Features

It also provides additional features such as user groups and additional security features:

- Configurable authentication (can use any type of authentication required, such as username or email)
- Authorization
- Activation of user *(optional)*
- Groups and group permissions
- "Remember me"
- User suspension
- Login throttling *(optional)*
- User banning
- Password resetting
- User data
- Interface driven - switch out your own implementations at will

### Installation

Installation of Sentry is very easy. We've got a number of guides to get Sentry working with your favorite framework or on it's own:

- [Install Sentry](https://cartalyst.com/manual/sentry#installation)

### Getting Started

- Use in [Laravel 4](https://cartalyst.com/manual/sentry#laravel-4)
- Use in [FuelPHP 1](https://cartalyst.com/manual/sentry#fuelphp-1.x)
- Use in [CodeIgniter 3](https://cartalyst.com/manual/sentry#codeigniter-3.0-dev)
- Use [natively (through composer)](https://cartalyst.com/manual/sentry#native)

### Upgrading

Currently, we do not have an upgrade method from Sentry 1, however we may be able to publish one before the stable release of Sentry 2.0. When upgrading between betas or release-candidates, please see [our changelog](https://github.com/cartalyst/sentry/blob/master/changelog.md).

### Support

We offer support through [our help forums](http://help.cartalyst.com), on [IRC at #cartalyst](http://webchat.freenode.net/?channels=cartalyst) and through GitHub issues (bugs only).

If you like Sentry, consider [subscribing](http://www.cartalyst.com/pricing) to our [Arsenal](http://www.cartalyst.com/arsenal). It allows us to keep creating awesome software and afford to eat at night. Subscribers also get **priority support** with all of our packages, both free and subscriber-only.

