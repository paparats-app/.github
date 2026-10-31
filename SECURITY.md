# Security policy

Paparats installs software on people's computers, so security reports come first.

## Reporting a vulnerability

Report privately through GitHub: open the affected repository's **Security** tab and choose
**Report a vulnerability**. Please do not open a public issue or discussion for a vulnerability.

Include:
- what you found and why it matters;
- how to reproduce it;
- the version, release or commit you tested.

We acknowledge a report within seven days and keep you posted until it is resolved. If you want
credit in the release notes, say how you would like to be named.

## Scope

- **The desktop client**, `paparats-app/paparats`: the installer, the updater, how the client
  verifies the catalog and the files it downloads.
- **The catalog**, `paparats-app/catalog`: the bot, the signed catalog and the GitHub Pages site.
- **A catalog entry that points to a malicious or tampered file.** Report it here as a
  vulnerability. We pull the entry first and investigate afterwards.

Vulnerabilities in the third-party apps themselves belong to their authors. Report them upstream,
in the app's own repository.

## Supported versions

Only the latest release gets fixes. The client updates itself, so a fix reaches users with the
next release.
