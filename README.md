# PoC for window.open() via postMessage

Proof-of-Concept for calling window.open() via postMessage.

### Browser support

| Browser             | Popup allowed |
|---------------------|---------------|
| Chrome 83           | ✅            |
| Edge 83             | ✅*           |
| Safari 13.1         | ✅            |
| iOS Safari 13.5     | ✅            |
| Firefox 77          | ❌            |

\* assumed based on the fact MS Edge uses same Chromium core as Google Chrome.

**Note:** Other browsers have not been tested as there is a lack of support in at least one major browser. 
