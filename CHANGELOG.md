# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [8.0.0](https://github.com/maidsafe/sn_messaging/compare/v7.0.1...v8.0.0) (2021-03-03)


### ⚠ BREAKING CHANGES

* **Seq:** Policy mutation operations are removed.

### Features

* **Seq:** upgrading sn_data_types to v0.16.0 and removing operations that are meant for mutating Seuquence's Policy ([306d8c1](https://github.com/maidsafe/sn_messaging/commit/306d8c16ea627f2aaed597d8c0df3698ab7d3a3e))

### [7.0.1](https://github.com/maidsafe/sn_messaging/compare/v7.0.0...v7.0.1) (2021-03-03)

## [7.0.0](https://github.com/maidsafe/sn_messaging/compare/v6.0.2...v7.0.0) (2021-02-26)


### ⚠ BREAKING CHANGES

* **api:** location scheme updated, breaking the current messaging api

### Features

* **api:** api updated ([4e11d0e](https://github.com/maidsafe/sn_messaging/commit/4e11d0ecf10eb1b9c5ead1ac5be0de1e079bff05))

### [6.0.2](https://github.com/maidsafe/sn_messaging/compare/v6.0.1...v6.0.2) (2021-02-26)

### [6.0.1](https://github.com/maidsafe/sn_messaging/compare/v6.0.0...v6.0.1) (2021-02-24)

## [6.0.0](https://github.com/maidsafe/sn_messaging/compare/v5.0.0...v6.0.0) (2021-02-24)


### ⚠ BREAKING CHANGES

* **location:** this adds a new variant to SrcLocation

### Features

* **location:** add support for accumulation at destination ([89cadad](https://github.com/maidsafe/sn_messaging/commit/89cadad9669295f2833f0a161acd252d04e4218a))

## [5.0.0](https://github.com/maidsafe/sn_messaging/compare/v4.0.5...v5.0.0) (2021-02-22)


### ⚠ BREAKING CHANGES

* **deps:** remove msgenvelope, change infrastructure msg

### Features

* **enduser:** add bootstrap msg variants ([129924e](https://github.com/maidsafe/sn_messaging/commit/129924e03eb020881322b1ce3d5412de70c02172))
* **enduser:** replace socketaddr with a hash ([45ac67f](https://github.com/maidsafe/sn_messaging/commit/45ac67f80dd010c3536a4632dcbf952d0f01a007))
* **messages:** implement location ([cf37569](https://github.com/maidsafe/sn_messaging/commit/cf37569d55515d35e5652c2c06f9ac3e8b3b7dbc))
* **messages:** remove MsgEnvelope ([d54b6c4](https://github.com/maidsafe/sn_messaging/commit/d54b6c42d119221f066d24109805b0995caf224b))


### Bug Fixes

* add string payload to invalid bootstrap error ([23ed16c](https://github.com/maidsafe/sn_messaging/commit/23ed16c2dd68f75c2554f7cc4d54c6fd6a9c7522))
* improve debug msg ([17daa0b](https://github.com/maidsafe/sn_messaging/commit/17daa0bca15a1d48a8869642969eca213196312e))
* post-rebase issues ([93578c7](https://github.com/maidsafe/sn_messaging/commit/93578c7b60fe8ec30dfbfd8d4371e8566284a9c1))


* **deps:** update sn_data_types ([555e4fb](https://github.com/maidsafe/sn_messaging/commit/555e4fbb3222ba0a46fd189c9c62bfd8052d9d19))

### [4.0.5](https://github.com/maidsafe/sn_messaging/compare/v4.0.4...v4.0.5) (2021-02-22)

### [4.0.4](https://github.com/maidsafe/sn_messaging/compare/v4.0.3...v4.0.4) (2021-02-18)

### [4.0.3](https://github.com/maidsafe/sn_messaging/compare/v4.0.2...v4.0.3) (2021-02-17)

### [4.0.2](https://github.com/maidsafe/sn_messaging/compare/v4.0.1...v4.0.2) (2021-02-16)

### [4.0.1](https://github.com/maidsafe/sn_messaging/compare/v4.0.0...v4.0.1) (2021-02-16)

## [4.0.0](https://github.com/maidsafe/sn_messaging/compare/v3.0.2...v4.0.0) (2021-02-15)


### ⚠ BREAKING CHANGES

* adds more infrastructure information to bootstrap and on section key errors
* Adds pk to messages and helper on MsgEnvelope

### Features

* add infrastructure information. ([9ca78b7](https://github.com/maidsafe/sn_messaging/commit/9ca78b78a8acf0cc3f6d9b9195a1483c66934d49))
* error messages related to target pk ([08d31d3](https://github.com/maidsafe/sn_messaging/commit/08d31d3f694bf92562499a498bc0b7dd903ff61c))
* make infra error its own type, use that in client::Error. ([122bc07](https://github.com/maidsafe/sn_messaging/commit/122bc0755078602a65275d4b7ccf2e8d759c8ef9))
* require a section key PK to be passed with all messages ([60f5240](https://github.com/maidsafe/sn_messaging/commit/60f5240ac8242d04e970773cdccfcb7ccd4a9e3e))

### [3.0.2](https://github.com/maidsafe/sn_messaging/compare/v3.0.1...v3.0.2) (2021-02-08)

### [3.0.1](https://github.com/maidsafe/sn_messaging/compare/v3.0.0...v3.0.1) (2021-02-08)

## [3.0.0](https://github.com/maidsafe/sn_messaging/compare/v2.0.0...v3.0.0) (2021-02-03)


### ⚠ BREAKING CHANGES

* **types:** moving client messages to its own module and publis namespace.

### Features

* **types:** adding Ping, NodeMessage and InfrastructureQuery definitions and support in serialisation ([dcd6b32](https://github.com/maidsafe/sn_messaging/commit/dcd6b321154714000d67c38137d1155433c4672a))

## [2.0.0](https://github.com/maidsafe/sn_messaging/compare/v1.6.1...v2.0.0) (2021-02-01)


### ⚠ BREAKING CHANGES

* rename money to token

* rename money to token ([eb53ef5](https://github.com/maidsafe/sn_messaging/commit/eb53ef577da48c9850e8997fcb91ebc6ae9fefd2))

### [1.6.1](https://github.com/maidsafe/sn_messaging/compare/v1.6.0...v1.6.1) (2021-02-01)

## [1.6.0](https://github.com/maidsafe/sn_messaging/compare/v1.5.5...v1.6.0) (2021-01-29)


### Features

* **genesis:** add msgs for genesis section init ([a808d3f](https://github.com/maidsafe/sn_messaging/commit/a808d3fbcf1ab10c8b21876ab177d97ffab47abc))
* **node_transfers:** add section payout error ([86114a5](https://github.com/maidsafe/sn_messaging/commit/86114a53593786ced19def470ddf262821d927ba))
* **nodeevents:** add SectionPayoutRegistered ([b782d19](https://github.com/maidsafe/sn_messaging/commit/b782d19cfa94a2d8b76cde714c3102dcfc9dc944))
* **rewards:** use share for payout validation ([041330b](https://github.com/maidsafe/sn_messaging/commit/041330bec25561e350a4fe28cc36cba4eb5f4d51))

### [1.5.5](https://github.com/maidsafe/sn_messaging/compare/v1.5.4...v1.5.5) (2021-01-15)

### [1.5.4](https://github.com/maidsafe/sn_messaging/compare/v1.5.3...v1.5.4) (2021-01-15)

### [1.5.3](https://github.com/maidsafe/sn_messaging/compare/v1.5.2...v1.5.3) (2021-01-13)

### [1.5.2](https://github.com/maidsafe/sn_messaging/compare/v1.5.1...v1.5.2) (2021-01-13)

### [1.5.1](https://github.com/maidsafe/sn_messaging/compare/v1.5.0...v1.5.1) (2021-01-13)


### Bug Fixes

* **verification:** verification of message_env checks underlying message, not itself ([ee90aef](https://github.com/maidsafe/sn_messaging/commit/ee90aef0c3164db4d57aba0022a6b82b941eec1b))

## [1.5.0](https://github.com/maidsafe/sn_messaging/compare/v1.4.0...v1.5.0) (2021-01-12)


### Features

* **errrors:** remove unexpectedNode error. ([effc838](https://github.com/maidsafe/sn_messaging/commit/effc838d7ff1d3297eced4026a5584f0ac90291b))

## [1.4.0](https://github.com/maidsafe/sn_messaging/compare/v1.3.0...v1.4.0) (2021-01-12)


### Features

* **errors:** add node relocation error ([cc8887f](https://github.com/maidsafe/sn_messaging/commit/cc8887f37b667242b861f8f9554c1cca0b64eb7d))

## [1.3.0](https://github.com/maidsafe/sn_messaging/compare/v1.2.0...v1.3.0) (2021-01-12)


### Features

* **serialisation:** add a size field to the wire message header and support only Msgpack serialisation type for protocol v1 ([b9eb6d6](https://github.com/maidsafe/sn_messaging/commit/b9eb6d6db6148a1554cf2d42e2a177f7ac6e0db7))
* **serialisation:** serialize to JSON with a wire message header ([806f3e4](https://github.com/maidsafe/sn_messaging/commit/806f3e4042c752cd69a3e0970e677e6affc37488))
* **serialisation:** support Msgpack serialisation type ([74870b1](https://github.com/maidsafe/sn_messaging/commit/74870b11bbe4e35d7887304bccf3d3e81362ac38))


### Bug Fixes

* **serialisation:** minor refactor and fix to Msgpack deserialisation logic ([d7c84e6](https://github.com/maidsafe/sn_messaging/commit/d7c84e6e1dd4f594613dac54ed2cc0ae0e958849))

## [1.2.0](https://github.com/maidsafe/sn_messaging/compare/v1.1.0...v1.2.0) (2021-01-05)


### Features

* **deps:** use crates.io sn_data_types ([0a4270a](https://github.com/maidsafe/sn_messaging/commit/0a4270a18100fa4d046d658f54553a8fcbcdf168))

## 1.1.0 (2021-01-05)


### Features

* more errors ([b8144bc](https://github.com/maidsafe/sn_messaging/commit/b8144bcbb88ee3bdcad3a9933c80c9fc2ac2ed76))
* **init:** initial port of messaging from sn_data_types ([10b874c](https://github.com/maidsafe/sn_messaging/commit/10b874c01e853a86f65947136498450bf5ff293d))

# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.
