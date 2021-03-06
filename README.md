[![Build Status](https://travis-ci.org/ChronixDB/chronix.storage.svg)](https://travis-ci.org/ChronixDB/chronix.storage)
[![Coverage Status](https://coveralls.io/repos/github/ChronixDB/chronix.storage/badge.svg?branch=master)](https://coveralls.io/github/ChronixDB/chronix.storage?branch=master)
[![Stories in Ready](https://badge.waffle.io/ChronixDB/chronix.storage.png?label=ready&title=Ready)](https://waffle.io/ChronixDB/chronix.storage)
[![Apache License 2](http://img.shields.io/badge/license-ASF2-blue.svg)](https://github.com/ChronixDB/chronix.storage/blob/master/LICENSE)
[ ![Download](https://api.bintray.com/packages/chronix/maven/chronix-storage/images/download.svg) ](https://bintray.com/chronix/maven/chronix-storage/_latestVersion)

# Chronix Storage
The Chronix Storage is an implementation of the Chronix API that uses Apache Lucene.
Hence the Chronix Storage can be used with Chronix Kassiopeia to store and query time series.

## Contributing
Is there anything missing? Do you have ideas for new features or improvements? You are highly welcome to contribute
your improvements, to the Chronix projects. All you have to do is to fork this repository,
improve the code and issue a pull request.

## Building Chronix Storage from Scratch
Everything should run out of the box. The only three things that must be available:
- Git
- JDK 1.8
- Gradle

Just do the following steps:

```bash
cd <checkout-dir>
git clone https://github.com/ChronixDB/chronix.storage.git
cd chronix.storage
gradlew clean build
```

## Maintainer

Florian Lautenschlager @flolaut

## License

This software is provided under the Apache License, Version 2.0 license.

See the `LICENSE` file for details.
