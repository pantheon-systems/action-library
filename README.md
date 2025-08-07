# Pantheon Action Library

A collection of GitHub Actions. Some specific to WordPress plugins, others more general use.

## WordPress Plugin Development

### [Validate Readme Spacing](https://github.com/pantheon-systems/validate-readme-spacing)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/validate-readme-spacing.svg)](https://github.com/pantheon-systems/validate-readme-spacing/releases/latest)

Validates that the heading section of your plugin's README.md has single-linebreak newlines handled correctly.

### [Build, Tag, & Release](https://github.com/pantheon-systems/plugin-release-actions/?tab=readme-ov-file#build-tag-and-release)

Commits a tag with optional build assets (NPM/Composer) and drafts a release.

[![Release Version](https://img.shields.io/github/release/pantheon-systems/plugin-release-actions.svg)](https://github.com/pantheon-systems/plugin-release-actions/releases/latest)

### [Prepare Dev](https://github.com/pantheon-systems/plugin-release-actions/?tab=readme-ov-file#prepare-dev)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/plugin-release-actions.svg)](https://github.com/pantheon-systems/plugin-release-actions/releases/latest)

Updates the development branch to be ready for the next release after releasing a new version of a plugin or module. This action search and replaces the version number across all the top-level files in the repo.

### [Release PR](https://github.com/pantheon-systems/plugin-release-actions/?tab=readme-ov-file#release-pr)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/plugin-release-actions.svg)](https://github.com/pantheon-systems/plugin-release-actions/releases/latest)

Drafts a release PR from a development branch to a release branch, This action search and replaces the version number across all the top-level files in the repo to drop the `-dev` from the version.

## Pantheon

### [Terminus](https://github.com/pantheon-systems/terminus-github-actions)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/terminus-github-actions.svg)](https://github.com/pantheon-systems/terminus-github-actions/releases/latest)

A GitHub Action for quickly installing and configuring the Pantheon CLI tool, Terminus.

## General Purpose

### [Package Updater](https://github.com/pantheon-systems/action-package-updater)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/action-package-updater.svg)](https://github.com/pantheon-systems/action-package-updater/releases/latest)

Tracks a list of arbratry dependencies in yaml and PRs updates automatically. Supports both GitHub releases and [PECL](https://pecl.php.net/).

### [Autotag](https://github.com/pantheon-systems/action-autotag)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/action-autotag.svg)](https://github.com/pantheon-systems/action-autotag/releases/latest)

Tags a release with [autotag-dev/autotag](https://github.com/autotag-dev/autotag).

### [PHP Compatibility](https://github.com/pantheon-systems/phpcompatibility-action)

[![Release Version](https://img.shields.io/github/release/pantheon-systems/phpcompatibility-action.svg)](https://github.com/pantheon-systems/phpcompatibility-action/releases/latest)

Runs [PHPCompatibility/PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) on source code.

## Actions We Love

### [WordPress.org Plugin Deploy](https://github.com/10up/action-wordpress-plugin-deploy) (10up)

Pushes plugin releases to WordPress.org with SVN.

### [WordPress Plugin Check Action](https://github.com/wordpress/plugin-check-action)

Replaces the (now deprecated) [Action WP.org Validator](https://github.com/pantheon-systems/action-wporg-validator). Runs a plugin against WordPress.org's validation standards.

### [WordPress.org Plugin Readme/Assets Update](https://github.com/10up/action-wordpress-plugin-asset-update) (10up)

Updates WordPress.org README without shipping a plugin update.

### [Validate WordPress Plugin "Tested Up To" Version](https://github.com/jazzsequence/action-validate-plugin-version) (jazzsequence)

Validates the "last tested up to" version against the current WordPress version and creates a PR with the change if the values don't match.
