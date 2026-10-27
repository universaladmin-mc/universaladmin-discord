<img src="assets/icon.png" alt="UniversalAdmin Discord" width="96" align="right">

# UniversalAdmin Discord

[![Build](https://github.com/universaladmin-mc/universaladmin-discord/actions/workflows/build.yml/badge.svg)](https://github.com/universaladmin-mc/universaladmin-discord/actions/workflows/build.yml)
[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Modrinth](https://img.shields.io/badge/Modrinth-universaladmin-discord-00AF5C)](https://modrinth.com/plugin/universaladmin-discord)

Posts UniversalAdmin's bans, mutes, reports, restarts and more to Discord - with a webhook in two minutes, or as a bot with two-way staff chat, /ban, /mute, /history from Discord and report buttons.

An official extension for [UniversalAdmin](https://github.com/universaladmin-mc/UniversalAdmin),
the free all-in-one admin plugin for Paper.

- **Documentation:** [https://universaladmin-mc.github.io/UniversalAdmin/extensions/discord/](https://universaladmin-mc.github.io/UniversalAdmin/extensions/discord/)
- **Download:** [Modrinth](https://modrinth.com/plugin/universaladmin-discord) or the
  [releases](https://github.com/universaladmin-mc/universaladmin-discord/releases) - put the
  jar next to UniversalAdmin in `plugins/`. UniversalAdmin's update check
  covers this extension too.
- **Bugs and ideas:** [UniversalAdmin's issues](https://github.com/universaladmin-mc/UniversalAdmin/issues)

## Building

```bash
./gradlew build   # build/libs/universaladmin-discord-<version>.jar
```

It compiles against the UniversalAdmin release named in `gradle.properties`
(from Modrinth's Maven repository); `-PuniversaladminJar=<path>` builds
against a local UniversalAdmin build instead. Releases: bump `version` in
`build.gradle.kts`, add a `CHANGELOG.md` section, tag `v<version>` - the
release workflow publishes to GitHub and Modrinth.

## License

[GNU GPL v3.0 or later](LICENSE).
