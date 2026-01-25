# Keystone Plugin Catalog

This repository contains the official plugin catalog for **Keystone CMS**.

The catalog is consumed by the Keystone admin dashboard to allow
administrators to discover and install plugins via Composer.

## How it works

- Plugins are listed in `plugins.json`
- Each entry describes a Composer package
- The CMS installs plugins using `composer require`
- This repository contains **metadata only**

## Adding a plugin

1. Fork this repository
2. Add your plugin to `plugins.json`
3. Open a pull request

All submissions are reviewed before being merged.
