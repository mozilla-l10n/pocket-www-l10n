# Developer notes

[![Pocket Marketing Pages](https://github.com/mozilla-l10n/mozl10n-linter/actions/workflows/pocket.yaml/badge.svg)](https://github.com/mozilla-l10n/mozl10n-linter/actions/workflows/pocket.yaml)

Pocket is translated in a similar way to Mozorg, but not entirely. This README captures things to bear in mind when working on localisation of Pocket-mode pages

## Translation service

For Pocket pages, all translations are handled by a vendor, rather than the community.

## Namespacing

Please ensure all strings for Pocket templates are `pocket-` at the start of their name. While there should be no clashes because the Mozorg and Pocket L10N configs are independent, this will give us extra protection and make discovery and replacement easier.
