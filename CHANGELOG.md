# Changelog

### v3.2.4

* Fix log `[object Object]` issue. See [meteor#10078](https://github.com/meteor/meteor/issues/10078).Thx @zodern.

### v3.2.0

* Remove dependency on `meteorhacks:meteorx`.
  [PR #7](https://github.com/meteor/meteor-apm-agent/pull/7)

* Use the Meteor core `ecmascript` package.

* Update `api.versionFrom` to Meteor 1.7.

### v3.1.1

* Use `Object.create(null)` rather than object initializer notation when
  initializing objects to store metric data.

### v3.1.0
* Replace jQuery with HTTP package (thx @ gbhrdt & jehartzog)

### v3.0.0
* Initial MDG release.
