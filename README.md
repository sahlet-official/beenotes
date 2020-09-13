# beenotes
application for beekeepers, building apiary structure, keeping of apiary bookkeeping, plan work and tasks related with apiary

Owner of the content of repository (code and other data that stores in current repository) doesn't allow to use, spread, modify code and data from repository.

To build client you need first:
-install node (v12.18.3 or greater) using nvm:
https://hackernoon.com/how-to-install-node-js-on-ubuntu-16-04-18-04-using-nvm-node-version-manager-668a7166b854

install cordova:
https://cordova.apache.org/

to build it for android install dependencies:
https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html

to build signed android app use Android Studio (choose build **aab** - not **apk**):
https://developer.android.com/studio/publish/app-signing
there is already created upload key *android-upload-keystore.jks* in folder *client/secrets/src*;
use *scrambler* to decript it from *client/secrets/crypt*

to build app for ios use VirtualBox and macOSX:
https://host-consult.ru/macos-high-sierra-virtualbox/
*while installing it may error happened: "This copy of the install macOS High Sierra application is damaged, and can’t be used to install macOS."*
*you can solve it using this info (don't forget to disable network connection): https://poznyaev.ru/blog/macos/oshibka-pri-chistoj-ustanovke-mac-os-x*
install dependencies:
https://cordova.apache.org/docs/en/latest/guide/platforms/ios/index.html
