# Changelog

## 4.1.9
Drop freshrequire stuff - doesn't work on either modern browserify or
nodejs.
Try to require chart.js/auto.Chart
Constructor accepts Chart.js class so we don't have to dynamically require.

## 4.0.0

Migrated to support chart.js v3.x.x, dropped support for 2.x.x
Removed the legacy API.

## 3.2.0

Another deploy for minor versions.

## 3.1.1

Added back legacy API to address a wrong version being deployed. See [#60](https://github.com/SeanSobey/ChartjsNodeCanvas/issues/60).

## 3.0.0

Rewrote `ChartJSNodeCanvas` API, the constructor and plugins in particular.
