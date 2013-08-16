# Steps for making a Debian package of Vert.x
1. Download Vert.x v2.0.0-final from https://bintray.com/vertx/downloads/distribution/2.0.0-final/files
2. Rename the downloaded file to `vert.x_2.0.0.final.orig.tar.gz` to comply Debian naming standards
3. Extract it and clone this repository as `debian/`
4. Run `$ dpkg-buildpackage`

# Distro compatibility
This package depends on java _java7-runtime-headless_ in Debian. This is provided by **openjdk-7-jre-headless** or by the package generated using [java-package](packages.debian.org/java-package)(v0.52).

**pull requests are welcome**
