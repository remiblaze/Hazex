# Hazex — Algorithmic Stereo Reverb

![Hazex](https://raw.githubusercontent.com/RemiBlaze/Hazex/main/hazex-ui-screenshot.png)

**A lush, atmospheric reverb for electronic music — from tight rooms to endless clouds.**

Hazex is a stereo reverb built on an 8-line feedback delay network with prime-length delay lines and Householder feedback mixing. It adds a pitch-shifting shimmer path, input-aware ducking, tempo-syncable pre-delay, and a modulated tail for lush, evolving spaces.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install
1. Go to the [latest release](https://github.com/RemiBlaze/Hazex/releases/latest).
2. Download **`Hazex_Installer.pkg`**.
3. Double-click it and follow the installer. Because it's **signed & notarized by Apple**, it installs cleanly — no security warnings, no right-click, no "Open Anyway."
4. Restart your DAW and rescan plug-ins.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ Features

| Control | Range | Default | What it does |
|---------|-------|---------|--------------|
| Size | 0–100% | 40% | Scales the delay-line lengths for tight rooms to large spaces |
| Decay | 0.1–10 s | 1.0 s | Reverb tail length |
| Damping | 0–100% | 28% | High-frequency absorption in the tail (brighter to darker) |
| Pre-Delay | 0–100 ms | 18 ms | Gap between the dry signal and reverb onset |
| Pre-Delay Sync | Off / 1/64 / 1/32 / 1/16 / 1/8 | Off | Locks pre-delay to host tempo |
| Tone | −100 to +100% | +20% | Post-reverb high-shelf for darker or brighter tails |
| Vapor | 0–100% | 80% | Stereo width, from mono-compatible to full stereo |
| Early Ref | 0–100% | 55% | Balance between early reflections and the late tail |
| Sub-Anchor | 20–500 Hz | 100 Hz | High-pass anchor that keeps low end tight |
| Ducking | 0–100% | 15% | Reverb ducks under a loud input, blooms when it stops |
| Duck Sensitivity | 0–100% | 50% | How readily the ducker responds to input level |
| Sat-Link | 0–100% | 0% | Drives the tail into saturation as it feeds back |
| HPF Link | 0–100% | 0% | Links a high-pass into the feedback path |
| Master Link | 0–150% | 0% | Master scaler over the modulation depths |
| Haziness | 0–100% | 8% | LFO modulation of the delay lines for movement |
| Shimmer | 0–100% | 0% | Pitch-shifted feedback for octave-up shimmer tails |
| Swell | 0–100% | 0% | Bar-synced upward swell of the wet mix |
| Reverse Bloom | 0–100% | 0% | Reversed, blooming envelope on the reverb |
| Freeze | On / Off | Off | Infinite sustain — holds the current tail |
| Mix | 0–100% | 25% | Dry/wet blend |
| Output | −24 to +6 dB | −0.5 dB | Output level |
| Bypass | On / Off | Off | Bypass all processing |

Plus a factory preset menu, **Save/Load** of user `.preset` files, and a **Randomize** button for quick exploration.

---

## 🔬 Under the Hood
- **8-line feedback delay network** with prime-length delay lines and a Householder feedback-mixing matrix for a dense, natural tail.
- **Per-line DC blockers** keep the feedback path clean and stable.
- **Pitch-shifting shimmer** feeds an octave-shifted signal back into the network.
- **LFO-modulated delay lengths** (Haziness) give the tail continuous movement.
- **Input-aware ducking** with adjustable sensitivity for vocals and busy mixes.
- **Tempo-syncable pre-delay** for rhythmic placement of the reverb.
- **Universal Binary** — native on Apple Silicon and Intel.

---

## 💻 System Requirements
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host (your DAW of choice)

---

## 🎚️ Factory Presets (21)

| Preset | Size | Decay | Character |
|--------|------|-------|-----------|
| Init | 45% | 1.6 s | Balanced default starting point |
| Forensic Room | 25% | 0.5 s | Tight, dry, controlled room |
| Small Room | 20% | 0.3 s | Short, natural space |
| Vocal Plate | 45% | 1.2 s | Smooth vocal plate with ducking |
| Large Hall | 75% | 3.0 s | Spacious concert hall |
| Cathedral | 90% | 6.0 s | Massive, dark stone reverb |
| Deep House Cloud | 70% | 4.0 s | Long, hazy deep-house wash |
| The Pumping Plate | 40% | 1.5 s | Heavily ducked pumping plate |
| Underwater Haze | 80% | 7.0 s | Dark, modulated, submerged tail |
| Ambient Wash | 85% | 8.0 s | Ethereal long tail with movement |
| Remi Blaze Smoke | 55% | 2.2 s | Atmospheric signature verb |
| Remi Blaze Space | 65% | 3.5 s | Wide, shimmering signature space |
| Ghost Clap | 35% | 0.8 s | Bright, gated clap ambience |
| Vacuum Suction | 60% | 4.5 s | Dark reverse-bloom pull |
| Acid Rain | 55% | 3.0 s | Bright, shimmering hazy tail |
| The Silver Lining | 70% | 5.0 s | Airy shimmer with deep modulation |
| Ghost Breathing | 50% | 2.5 s | Breathing, ducked ghost tail |
| Static Haze | 60% | 2.5 s | Steady, modulated haze |
| The Heartbeat | 55% | 1.8 s | Pulsing, linked-modulation verb |
| Pushed Iron | 50% | 2.0 s | Driven, saturated metallic tail |
| The Pushed 80s Plate | 55% | 2.2 s | Saturated retro plate |

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/Hazex/issues)** tab with your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
