# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-filter-input`, published as `gizmocraft/zendframework1-filter-input`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-filter-input` to `gizmocraft/zendframework1-filter-input`. It now requires `gizmocraft/zendframework1-loader` `^2.0.0`, `gizmocraft/zendframework1-registry` `^2.0.0`, `gizmocraft/zendframework1-translate` `^2.0.0`, `gizmocraft/zendframework1-validate` `^2.0.0` and `gizmocraft/zendframework1-filter` `^2.0.0`.

### Other changes

- No public signature changes. `Zend_Filter_Input` needed no code changes for PHP 8.5 or 8.6.
- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes (`#[Group]`, `#[DoesNotPerformAssertions]`).
- CI runs PHP 8.5 and 8.6.
