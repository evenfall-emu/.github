<p align="center">
  <img src="banner.png" alt="Evenfall" width="100%">
</p>

Evenfall builds open-source emulators for classic consoles. Each one is written
from scratch, test-first, against published hardware documentation and test
ROMs, around a deterministic core that runs natively and in the browser. Every
emulator keeps its own name.

### Emulators

| Emulator | Console | Highlights |
|---|---|---|
| **[ZiGBA](https://github.com/evenfall-emu/zigba)** | Game Boy Advance | Cycle-aware core in Zig · original HLE BIOS · [`@evenfall/gba`](https://www.npmjs.com/package/@evenfall/gba) WebAssembly SDK · [play in the browser](https://zigba.ursid.ai) |

### Principles

- **Accuracy from evidence.** Behavior follows CPU manuals, hardware
  documentation and test ROMs. Other emulators are comparisons, never code to
  copy.
- **Deterministic cores.** The same inputs produce the same pixels, samples and
  saves on every host, which makes every bug reproducible.
- **Built to embed.** Each core is a library first: native, WebAssembly and
  JavaScript.
- **Free software.** Emulator code is licensed under the
  [GNU AGPL, version 3 or later](https://www.gnu.org/licenses/agpl-3.0.html).
- **Your games, your files.** No BIOS images or games are distributed.

### Contact

General questions: [contact@evenfall-emu.org](mailto:contact@evenfall-emu.org)
· Security reports: [security@evenfall-emu.org](mailto:security@evenfall-emu.org)
