## 1.0.0 (unreleased)

- Feature: Add support for Rails 7
- Change: Drop support for older versions
- Chore: Test against MySQL 8
- Fix: Handle ActiveRecord::ConnectionNotEstablished errors too
- Fix: Do not retry on ActiveRecord::StatementTimeout errors

## 0.5.0 (Jan 29, 2020)

- Change error message for Rails 6.0
- Load database config from db_config instead
- Add Active Record 6.0 and master to build matrix

## 0.4.2 (Aug 15, 2018)

- Add activerecord-5.2 test
- Add error messages accessor
- Fix mysql2 dependency
- Added "Connection was killed" as an error string to reconnect on.

## 0.4.1 (Aug 8, 2016)

- Support AR 5.0 (RP#5 @ssig33)
- Fix test (use docker-compose)

## 0.4.0 (Mar 22, 2016)

- Remove `retryable_transaction`
- Disable support AR 3.x 4.0

## 0.3.3 (Jan 18, 2014)

- use BigDecimal for sleep
- add handling error ('The MySQL server is running with the --read-only...')

## 0.3.1 (Jan 9, 2014)

- Retry mode is added

## 0.3.0 (Jan 9, 2014)

- Retry is disabled by default
- Read-only mode is added

## 0.2.0 (Jan 4, 2014)

- Retry transaction is supported

## 0.1.0 (Oct 11, 2013)

- activerecord-mysql-reconnect is released
