# substance-artifacts

The [Substance](https://github.com/kirill-grouchnikov/substance) look and feel artifacts

The purpose of this project is simply to publish various Substance look and feel artifacts to a public repository so they can be easily used by dependent projects.

## Usage

By default, the Substance look and feel primary artifact is published (e.g. _substance-<version>.jar_).  For example, to publish version 7.1.01 of the Substance look and feel primary artifact to Bintray, use the following command:

    $ ./gradlew -Pversion=7.1.01 bintrayUpload

The secondary artifacts may be published by specifying the `packageName` project property.  For example, to publish version 7.1.01 of the Substance look and feel lite artifact to Bintray, use the following command:

    $ ./gradlew -PpackageName=lite -Pversion=7.1.01 bintrayUpload
