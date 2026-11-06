# webxsid.github.io

Keeps Crona for macOS's old update feed address working after the project moved to the
[`crona-app`](https://github.com/crona-app) organization.

Builds before `v1.1.0-beta.3` check `https://webxsid.github.io/crona-macos/appcast.xml`.
The workflow here copies the live feed from `crona-app.github.io/crona-macos` into
`crona-macos/appcast.xml`, so those installs still see the update that moves them to
`https://crona.work/updates/mac/appcast.xml`. Download and release-notes links inside the
feed already point at their new homes.

Once old installs have updated, this repository can be archived.
