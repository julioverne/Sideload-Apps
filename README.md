# Sideload Apps

extra features for Apps by loading library on main app executable

Deezer v001
------

* Fully Premium Features

Spotify v004
------

* Premium Features (except Music offline)

Pandora v007
------

* Unrestricted Country
* No ADs
* High Quality Stream
* Downloads
* Unlimited Skips
* No delay Button Skip
* No 180 minutes timeout

SoundCloud v007
------

* Fully Premium Features
* Unrestricted Country

Napster v002
------

* Fully Premium Features

MovieBox v001
------

* No ADs

How to use
------

* Rename App file extension .ipa to .zip and Extract
* Open main App Executable(like: Payload/AppName.app/AppName) on any Hex Editor
* Replece all occurencies of string "/usr/lib/libSystem.B.dylib" to "@executable_path/Sys.dylib" and Save Changes
* Copy file Sys.dylib to same Dir of App Executable(like: Payload/AppName.app/)
* Compress back to zip and rename compressed file extension .zip to .ipa
* Use [iOS App Signer](https://dantheman827.github.io/ios-app-signer/) to sign and install with iTunes/Xcode/other.

