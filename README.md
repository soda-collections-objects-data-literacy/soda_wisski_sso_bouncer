# SODA WissKI SSO Bouncer

This module extends SSO (Single Sign-On) functionality for WissKI instances within the SODa ecosystem.

## Requirements

- Drupal >10.2 or 11
- WissKI instance
- PHP 8.3 or higher
- Drupal openid module

## Installation

1. Place the module in your Drupal installation's `web/modules/custom` directory
2. Enable the module through the Drupal admin interface or using Drush:
   ```bash
   drush en soda_wisski_sso_bouncer
   ```
## Usage

Everything is automatically, checks if user has valid keycloak groups if not, user is rejected.

## License

This module is licensed under the GNU General Public License v2 or later.
