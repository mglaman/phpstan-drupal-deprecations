# phpstan-drupal-deprecations

Streamlines configuration for deprecation testing.

## Usage

Add `phpstan.neon` to your Drupal project. Then configure it to include either the `deprecation` or `rules_and_deprecation` testing configurations.

### Testing deprecations only

```neon
includes:
	- vendor/mglaman/phpstan-drupal-deprecations/deprecation_testing.neon
```

### Inspection rules and deprecations

```neon
includes:
	- vendor/mglaman/phpstan-drupal-deprecations/rules_and_deprecations_testing.neon
```