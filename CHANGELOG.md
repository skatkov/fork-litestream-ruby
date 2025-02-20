## [Unreleased]

## [0.5.4] - 2024-04-18

- Remove old usage of config.database_path ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/18))
- Ensure that executing a command synchronously returns output ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/20))

## [0.5.3] - 2024-04-17

- Fix bug with Rake tasks not handling new kwarg method signatures of commands

## [0.5.2] - 2024-04-17

- Add a `verify` command and Rake task ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/16))
- Allow any command to be run either synchronously or asynchronously ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/17))

## [0.5.1] - 2024-04-17

- Add `databases`, `generations`, and `snapshots` commands ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/15))

## [0.5.0] - 2024-04-17

- Add a `restore` command ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/14))
- Ensure that the #replicate method only sets unset ENV vars and doesn't overwrite them ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/13))

## [0.4.0] - 2024-04-12

- Generate config file with support for multiple databases ([@fractaledmind](https://github.com/fractaledmind/litestream-ruby/pull/7))

## [0.3.3] - 2024-01-06

- Fork the Litestream process to minimize memory overhead ([@supermomonga](https://github.com/fractaledmind/litestream-ruby/pull/6))

## [0.1.0] - 2023-12-11

- Initial release
