# BintrayPluginPlayground

Sample project that demonstrates problem reported here: https://github.com/novoda/bintray-release/issues/93

Steps to repro:
- clone this project
- execute `./gradlew clean build :library:bintrayUpload -PbintrayUser=DUMB -PbintrayKey=DUMB -PdryRun=true`
- Observe build failure
- Cry out loud
- Come back next day and check bug progress [here](https://github.com/novoda/bintray-release/issues/93)
- go to step 1

