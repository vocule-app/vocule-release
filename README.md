# Vocule — releases

Binaries for [Vocule](https://github.com/mysideproject/vocule), a free on-device
voice-dictation app for macOS.

Nothing is committed to this repository's tree: installers live as assets on the
[Releases](../../releases) page, and updates are delivered through the Sparkle
appcast at <https://vocule-landing.pages.dev/appcast.xml>.

- **First install:** `Vocule-<version>-arm64.dmg` (Developer ID signed,
  notarized, stapled).
- **Auto-update archive:** `Vocule-<version>-arm64.zip` — what Sparkle
  downloads; notarized and stapled, signed with Vocule's Ed25519 key.

Vocule is a fork of [YapToText](https://github.com/ryleighnewman/YapToText)
(GPL-3.0) by Ryleigh Newman, and stays under the GPL-3.0.