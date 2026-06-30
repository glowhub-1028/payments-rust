# Changelog

## [1.105.2](https://github.com/glowhub-1028/payments-rust/compare/v1.107.1...v1.105.2) (2026-06-30)


### ⚠ BREAKING CHANGES

* **rust:** flat positional methods (e.g. client.credit_entitlements_balances_create_ledger_entry(..)) are replaced by the fluent builder API; all call sites must migrate.

### Features

* **api:** add tax_id_business_name and tax_id_format_name to CalculateSessionResponse ([cbf3b49](https://github.com/glowhub-1028/payments-rust/commit/cbf3b497a0cf97cc4d7581ef12b9d20fc5e1646b))
* **api:** regenerate SDK from latest OpenAPI spec ([e8d70dd](https://github.com/glowhub-1028/payments-rust/commit/e8d70dd2c06c9ab859fb6dca2bfe64ddcfa7aa34))
* **api:** regenerate SDK from latest OpenAPI spec ([f5a6612](https://github.com/glowhub-1028/payments-rust/commit/f5a6612abe0179b6fc201e15c8206ca75cdd1aab))
* **api:** regenerate SDK from latest OpenAPI spec ([fd96053](https://github.com/glowhub-1028/payments-rust/commit/fd9605331f4bc0d00b498aa6c0fb4c0cde277127))
* **api:** regenerate SDK from latest OpenAPI spec ([b2209a6](https://github.com/glowhub-1028/payments-rust/commit/b2209a61215338a5ba9d64a65b65fb879e63d7fb))
* **rust:** fluent resource-chain builder API ([254d430](https://github.com/glowhub-1028/payments-rust/commit/254d4302b6b37108842c30bdd6ef3aacbd482053))
* **rust:** test-mode Environment support and binary response decoding ([#14](https://github.com/glowhub-1028/payments-rust/issues/14)) ([229ebe7](https://github.com/glowhub-1028/payments-rust/commit/229ebe7c489b8924a9d78214788cc7182078bb04))


### Bug Fixes

* **api:** add allow_editing_addons checkout flag and refine schema descriptions ([a029fec](https://github.com/glowhub-1028/payments-rust/commit/a029fec6cd1c87b3dfebb08959986622b1d83de8))
* **api:** add allow_editing_addons checkout flag and refine schema descriptions ([5c3d5e5](https://github.com/glowhub-1028/payments-rust/commit/5c3d5e5b98febff3d5b53a871fa3532206556a20))


### Chores

* align version with API line (1.105.0) ([e1d7a61](https://github.com/glowhub-1028/payments-rust/commit/e1d7a615804103edb2bf72f7dc4751b0d70eab61))
* release rust SDK as 1.105.1 ([7c76e98](https://github.com/glowhub-1028/payments-rust/commit/7c76e9832bda4633107b9439fd74cd8250d9cdd2))


### Documentation

* align generated README with released version 1.105.0 ([#6](https://github.com/glowhub-1028/payments-rust/issues/6)) ([5029d25](https://github.com/glowhub-1028/payments-rust/commit/5029d259fe94ec3a89dbcbadc85d694c9e49e14d))

## [1.107.1](https://github.com/dodopayments/dodopayments-rust/compare/v1.107.0...v1.107.1) (2026-06-27)


### Bug Fixes

* **api:** add allow_editing_addons checkout flag and refine schema descriptions ([8059f23](https://github.com/dodopayments/dodopayments-rust/commit/8059f23bfbd88ced9cca601fa1347f3bfb7f3d62))
* **api:** add allow_editing_addons checkout flag and refine schema descriptions ([db1f242](https://github.com/dodopayments/dodopayments-rust/commit/db1f2425f5e8913fd83c14bbc639759b6056a035))

## [1.107.0](https://github.com/dodopayments/dodopayments-rust/compare/v1.106.0...v1.107.0) (2026-06-23)


### Features

* **api:** regenerate SDK from latest OpenAPI spec ([1e8fe02](https://github.com/dodopayments/dodopayments-rust/commit/1e8fe027f28ecfd8e98b6608e4a1525a58ccdc74))
* **api:** regenerate SDK from latest OpenAPI spec ([433dc1b](https://github.com/dodopayments/dodopayments-rust/commit/433dc1b77231e9dfaa673e3dd6e21e7e97263dc1))

## [1.106.0](https://github.com/dodopayments/dodopayments-rust/compare/v1.105.2...v1.106.0) (2026-06-19)


### Features

* **api:** regenerate SDK from latest OpenAPI spec ([3ceb106](https://github.com/dodopayments/dodopayments-rust/commit/3ceb106997c9b3c3be2f7174ec98199464ebcefe))
* **api:** regenerate SDK from latest OpenAPI spec ([097cdf9](https://github.com/dodopayments/dodopayments-rust/commit/097cdf923963a432607c7c2d7f3b3479413a241a))

## [1.105.2](https://github.com/dodopayments/dodopayments-rust/compare/v1.105.1...v1.105.2) (2026-06-18)


### ⚠ BREAKING CHANGES

* **rust:** flat positional methods (e.g. client.credit_entitlements_balances_create_ledger_entry(..)) are replaced by the fluent builder API; all call sites must migrate.

### Features

* **rust:** fluent resource-chain builder API ([53cba1f](https://github.com/dodopayments/dodopayments-rust/commit/53cba1f65dcfa27c2cf99ac76e9a4520c684bda9))

## [1.105.1](https://github.com/dodopayments/dodopayments-rust/compare/v1.105.0...v1.105.1) (2026-06-17)


### Features

* **rust:** test-mode Environment support and binary response decoding ([#14](https://github.com/dodopayments/dodopayments-rust/issues/14)) ([f289dc2](https://github.com/dodopayments/dodopayments-rust/commit/f289dc22e3fc3df1790194df38501f0e2e95c8a4))


### Chores

* release rust SDK as 1.105.1 ([b7583ca](https://github.com/dodopayments/dodopayments-rust/commit/b7583ca25c32f2490e3df3610569ca3057d57f38))


### Documentation

* align generated README with released version 1.105.0 ([#6](https://github.com/dodopayments/dodopayments-rust/issues/6)) ([57d0638](https://github.com/dodopayments/dodopayments-rust/commit/57d063898cd46c585b511c5aca95b5d4813c8957))

## [1.105.0](https://github.com/dodopayments/dodopayments-rust/compare/v0.1.0...v1.105.0) (2026-06-17)


### Chores

* align version with API line (1.105.0) ([f52def9](https://github.com/dodopayments/dodopayments-rust/commit/f52def92d73d72801a16708d10612e68bb734e98))

## [0.1.0](https://github.com/dodopayments/dodopayments-rust/compare/v0.0.1...v0.1.0) (2026-06-16)


### Features

* **api:** add tax_id_business_name and tax_id_format_name to CalculateSessionResponse ([060b310](https://github.com/dodopayments/dodopayments-rust/commit/060b31096d83ffd73e33fde9d346a3fd20b5431a))

## Changelog
