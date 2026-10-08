---
"@zag-js/dialog": patch
"@zag-js/drawer": patch
---

Fixed issue where the backdrop blocked pointer interaction with the page when `modal` is `false`. The backdrop is now
hidden for non-modal dialogs and drawers.
