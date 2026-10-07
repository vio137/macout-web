# MAC-OUT website

A static product site and 23-scene interactive presentation for MAC-OUT 1.1.0.

## Run

Serve this folder with any static server, or enable GitHub Pages on the root of `main`.
The presentation has a direct entry at `#presentation`.

No build step, paid library, analytics, third-party scripts or network access is required.
Fonts are self-hosted. The browser simulations do not modify or inspect network interfaces.
Sound is opt-in and synthesized locally using Web Audio. Reduced-motion preferences are honored.

## Presentation controls

- Right/left arrows or Page Down/Page Up: next/previous
- Home/End: first/last scene
- Escape: exit
- Horizontal swipe: next/previous on touch screens
- Scenes: jump to a chapter
- Play: 14-second auto-advance; Pause stops it
- Fullscreen where supported

## Sources

- https://github.com/vio137/macout/releases/tag/v1.1.0
- https://github.com/vio137/macout/tree/v1.1.0
- https://github.com/vio137/macout/blob/main/ARCHITECTURE.md
- https://github.com/vio137/macout/blob/main/INSTALL.md
- https://www.rfc-editor.org/rfc/rfc9542.html
- https://www.rfc-editor.org/rfc/rfc9797.html
- https://manpages.debian.org/bookworm/macchanger/macchanger.1
- https://networkmanager.dev/docs/api/latest/settings-802-3-ethernet.html

App screenshots are real Ubuntu GTK/Xvfb captures from the 1.1.0 repository.
The MAKAUT JPEG is used unchanged. Neither the logo nor a demonstration address implies endorsement or hardware identity.

Made for Arnab Mandal's CA-1 presentation. Special thanks to Dr. Nabanita Ganguly.


## October 2026 educational expansion
23 editable HTML scenes and a source-verified MAC/macchanger foundations section, function atlas and conditional command trace. Original animations and simulation interactions are preserved. Official current MAKAUT emblem: https://makautwb.ac.in/notun/images/logo.png (observed on the university homepage https://makautwb.ac.in/). The user's original larger project logo is retained in the presentation. Neither logo implies university endorsement.

Command descriptions are traced to macout_app/backend.py and services.py on https://github.com/vio137/macout. The browser is an educational simulator only; it executes no network commands.
