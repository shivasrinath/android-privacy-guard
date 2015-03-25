# Source #

Main Repository: https://github.com/thialfihar/apg

Fork (should not be used as production release): https://github.com/dschuermann/openpgp-keychain

## Contribute ##

Fork APG on
https://github.com/thialfihar/apg or https://github.com/dschuermann/openpgp-keychain and do a pull request. I will merge your changes back into the main project.

## Build using Ant ##

  * Execute "ant -Dsdk.dir=/opt/android-sdk/ release" with the appropriate paths.

  * Alternatively you could add a file local.properties with the following lines, altered to your locations of the SDK:
```
sdk.dir=/opt/android-sdk
```

  * and execute "ant release"