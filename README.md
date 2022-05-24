Welcome to USBL Wallet, a standalone USBL payment app for your Android device!

This project contains several sub-projects:

**wallet**: The Android app itself. This is probably what you're searching for

**common**: Contains common components used by integrations

**integration/liquid** Contains the liquid integration

**integrations/uphold** Contains the uphold integration

**market**: App description and promo material for the Google Play app store

**integration-android**: A tiny library for integrating USBL payments into your own Android app (e.g. donations, in-app purchases).

**sample-integration-android**: A minimal example app to demonstrate integration of digital payments into your Android app.

You can build the production version using Gradle:

./gradlew assembleProdRelease

The built apks will be in wallet/build/outputs/apk
