ridebuild
=========

RideBuild

Install Requirements
====================

1. npm install -g cordova ionic


run on device:

    ionic run ios

run on emulator:

    ionic emulate ios

(all commands work with android too - both SDKs must be installed)

  Run in Browser:

    cd in root directiony: node scripts/web-server.js 

Should start local server on :8000 nav to www/index.html

If you want to run it on your iphone: see me for provisioning profile

Using the social plugin for phonegap found here 

https://github.com/EddyVerbruggen/SocialSharing-PhoneGap-Plugin

Other things
====================

Phonegap is a little weird when it comes to where files live. The root www folder is where our working directory is but they get copied to their Platform www directories at build/runtime. Sometimes you have to force the issue with a prepare command


cordova = phonegap

cordova prepare ios : a command that preps everything in your root/www folder 
