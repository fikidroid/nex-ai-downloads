# NEX AI — Public Releases

Public release distribution for **NEX AI** — an AI-powered audio visualizer,
video loop generator, and live streaming engine for Windows and macOS.

> 🌐 **Website:** [nexai-studio.vercel.app](https://nexai-studio.vercel.app)  
> 📦 **Latest release:** [Download here](../../releases/latest)  
> 🐙 **Releases archive:** [All versions](../../releases)

This repository hosts the public release artifacts (`.exe`, `.dmg`) under
the [Releases](../../releases) tab. The application source code is maintained
in a separate, private repository.

---

## Platform Requirements

- **Windows:** Windows 10 or 11 (64-bit)
- **macOS:** macOS 12 Monterey or later
  - Apple Silicon (M1 / M2 / M3 / M4)
  - Intel (2015–2020)

---

## Support

For installation help, licensing questions, or feature requests, please visit
[nexai-studio.vercel.app](https://nexai-studio.vercel.app).

For bug reports relating to a specific release, you may open an issue in this
repository referencing the affected version.

---

## Third-Party Software

NEX AI uses the following open-source software:

### FFmpeg

NEX AI uses [FFmpeg](https://ffmpeg.org) — a complete cross-platform solution
to record, convert, and stream audio and video.

- **License:** GNU General Public License version 3 (GPL v3) — full text at
  <https://www.gnu.org/licenses/gpl-3.0.txt>
- **Source code:**
  - <https://ffmpeg.org/download.html>
  - <https://github.com/FFmpeg/FFmpeg>
  - <https://github.com/BtbN/FFmpeg-Builds>

The FFmpeg binaries bundled with NEX AI are obtained, **without modification**,
from the [FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) automated
build project, which compiles binaries from upstream FFmpeg sources.

In compliance with **GPL v3 Section 6**, source code corresponding to the
bundled FFmpeg version is freely available at the URLs above for at least
three (3) years from the date of distribution of any release.

To identify the exact FFmpeg version bundled with a specific build, run
the following command from the application's `bin/` (Windows) or
`Resources/bin/` (macOS) directory:

```
neuralcore.exe -version            (Windows)
neuralcore_mac_arm -version        (macOS Apple Silicon)
neuralcore_mac_intel -version      (macOS Intel)
```

A copy of this third-party notice is also bundled inside each installer at
`resources/THIRDPARTY.txt` (Windows) or `Contents/Resources/THIRDPARTY.txt`
(macOS).

---

## License

The **NEX AI application** is proprietary software.
Copyright © 2016–2026 Kiki Mulyana. All rights reserved.

Distribution, modification, reverse engineering, decompilation, or
disassembly of the NEX AI application, its compiled binaries, or its bundled
assets without prior written permission from the copyright holder is
prohibited. Use of the application is subject to the End User License
Agreement shown during installation and accessible from within the
application.

The proprietary license of NEX AI applies **only** to the NEX AI application
itself. It does **not** restrict the open-source software listed in the
*Third-Party Software* section above, which remain governed by their
respective open-source licenses.

---

## Acknowledgments

NEX AI gratefully acknowledges the FFmpeg developers and contributors,
the FFmpeg-Builds maintainers, and the wider open-source video and audio
processing community whose work makes this product possible.
