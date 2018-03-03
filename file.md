# Legal & Liability

- [] Fonts are documented in the README and approved in the SOW.
- [] Icons are documented in the README and approved in the SOW.
- [] Third-party libraries are documented in the README and approved in the SOW.
- [] All production accounts are owned by the client. (Heroku, AWS, Google, iTunes Connect, etc.)
- [] All staging accounts are owned by the client. (Heroku, AWS, Google, iTunes Connect, etc.)
- [] All development accounts are owned by the client. (Heroku, AWS, Google, iTunes Connect, etc.)
- [] All API keys belong to the client for all services. (Facebook, Crashlytics, Google, Segment, etc.)
- [] In release builds, all API keys and dependencies are pointing to production configurations. (Facebook, Crashlytics, Google, etc.)

# Accessibility

- [] Android: The app fully supports Google TalkBack.
- [] iOS: The app automatically adjusts font sizes based on DynamicType settings.
- [] iOS: The app fully supports VoiceOver.
- [] Text protection is enabled for text with low-contrast backgrounds.

# Design

- [] The app matches the design spec (deck and Zeplin assets) pixel-for-pixel.
- [] The layout supports all supported device types and screen sizes as defined in the README.
- [] iOS: The app layout supports the in-call status bar.

# Security

- [] The app uses HTTPS for all web service requests.
- [] API keys are not stored in the source code and are included dynamically at build-time.
- [] Android: Authentication keys and passwords are on file at Livefront with Mike/Sam/Adrianne.
- [] Android: Release builds use code obfuscation.
- [] iOS: Provisioning profiles, certificates, and passwords for debug builds are on Dropbox under Engineering/Apple for the project.
- [] iOS: Provisioning profiles, certificates, and passwords for release builds are on Dropbox under Engineering/Apple for the project.
- [] iOS: The app stores sensitive data like authentication tokens in Keychain.
- [] Relevant usernames and passwords for third-party services are on file at Livefront with Mike/Sam/Adrianne.

# Quality

- [] The README is complete and fully up-to-date.
- [] The test plan is complete and fully up-to-date.
- [] 100% unit test coverage.
- [] All unit tests pass.
- [] Memory profiling is complete.
- [] Open source acknowledgements are current and visible to end users.
- [] The upgrade path works properly. (i.e. Upgrading from previous versions works as expected.)
- [] Locally stored data is migrated successfully when upgrading from a previous version.
- [] The fresh install path works properly.
- [] Testing is complete on all supported OS versions.
- [] Testing is complete on all supported device types (e.g. iPhone X and iPhone SE).
- [] Testing is complete on all supported device orientations.
- [] Testing is complete on all supported platforms (e.g. tablet and phone).
- [] The app shows reasonable and helpful error messages when used offline.
- [] The app is configured to allow geofence and location testing with mock data.
- [] A linter is used to enforce code style.
- [] Analytics are being collected properly.
- [] Android: The app has been tested and works properly for release builds (i.e. after code obfuscation).
- [] iOS: No Auto Layout constraint warnings occur at runtime.
- [] iOS: Stale Keychain values are purged on reinstall.
- [] iOS: The app works properly if a debug build is installed, the debug build is removed, and a production build is installed.
- [] iOS: The app doesn't request permission for features that are not used. (e.g. Only request location permission in the Info.plist if location permission is requested from the user.)

# Versioning & Release

- [] The status of Pivotal Tracker stories is correct for this version.
- [] The new features in this version have been documented in the CHANGELOG.
- [] The version number has been bumped in the source code and associated project and CHANGELOG changes exist as a pull request.

# GitHub

- [] All PRs have been reviewed and merged.
- [] Branches for merged PRs have been deleted.

# Fragile Things

- [] No client-side validation is performed on login screens.
- [] Universal Link handling is case-insensitive.
- [] Universal Link handling works for "www" and naked domains.
- [] New devices (no previous installation) correctly register for push notifications.
