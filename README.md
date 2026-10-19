# Felucca – ODeath Wavetable Mod

A community wavetable synthesizer modification for the M-VAVE FM-1, built on **Felucca**.

**Original firmware and original web installer:** © 2026 **Leo Kuroshita (@kurogedelic), Hügelton Instruments** — [Felucca](https://github.com/hugelton/Felucca). **Wavetable modification:** ODeath.

## Install

**[Open the GitHub Pages installer](https://gybe808-dotcom.github.io/FeluccaWavetableOdeathMod/)** (once Pages is enabled from `main`, `/ (root)` in repository Settings → Pages).

Use Chrome or Edge desktop, connect an M-VAVE FM-1 via USB, and press Install. The included SOLID 20 v0.7.5 package is checked against its published SHA-256 before any installation is enabled. Do not unplug while flashing. Firmware modifications are at your own risk; have recovery tools available.

**Firmware version:** SOLID 20, v0.7.5. 20 waveforms, morphing, 4-voice wavetable synthesis, 8 bandlimiting levels and 9 presets.

## Provenance & licensing

This is **not an official Felucca release**. Felucca is the original firmware and remains the foundation of the project. Its firmware architecture, UI, effects, hardware integration, WebMIDI flashing code (`web/fm1ota.js`), and firmware package reader (`web/fm1pkg.js`) are the work of Leo Kuroshita / Hügelton Instruments and other credited contributors. The installer is adapted from [Felucca's web installer](https://github.com/hugelton/Felucca/tree/main/web), not independently developed by ODeath.

Original authors and license obligations: [Felucca CREDITS.md](https://github.com/hugelton/Felucca/blob/main/CREDITS.md) · [LICENSING.md](https://github.com/hugelton/Felucca/blob/main/LICENSING.md) · [GPL-3.0-only](https://github.com/hugelton/Felucca/blob/main/LICENSE).

The included `firmware/felucca.fwsc` was built from a modification of Felucca and contains components from the JieLi AC79 SDK. See the [Felucca licensing breakdown](https://github.com/hugelton/Felucca/blob/main/LICENSING.md) for the Apache-2.0 SDK components and other included works.

**Public source-release requirement:** This binary release must be accompanied by its **complete corresponding modified source** (including build scripts, modifications, and required submodules), licensed consistently with Felucca's GPL-3.0-only terms. **The installer alone is not a complete source release.** Do not advertise this repository as a complete compliant firmware source distribution until the matching source has been published here.

## Verified release binary

- Path: `firmware/felucca.fwsc`
- Size: `610086` bytes
- SHA-256: `0a17a97e8603df570539b35f8d0a9cf12d1cb538db5bbe357c3f0e3f9b9a1dad`
- Package identity: `FM-1_900`

No installations on the user's Windows or Ubuntu environments are required to use this website.

## Acknowledgments

Special thanks to **Joakim Eriksson** for the separate [FM-1 emulator](https://github.com/joakimeriksson/fm1-emu), used during development. The emulator is not part of this installer.

M-VAVE and FM-1 are trademarks of their respective owners. No endorsement or warranty is implied.
