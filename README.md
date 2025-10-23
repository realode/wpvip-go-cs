# Realode PHP Coding Standard

This coding standard is based on WordPress VIP Go with small tweaks.

## Installation

Install the package using `composer`:

```bash
composer require --dev realode/wpvip-go-cs
```

## Usage

Reference it in the project's `phpcs.xml`:

```xml
<?xml version="1.0"?>
<ruleset name="Realode Package Name">
	<rule ref="vendor/realode/wpvip-go-cs/phpcs.xml.dist"/>
</ruleset>
```