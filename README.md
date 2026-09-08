# Homespire digital business cards — staging

Preview build for stakeholder review. **Not production.**

Cards live at `/<slug>/`, e.g. https://mmiller-hmc.github.io/cards/otmane/

Generated from [mmiller-HMC/digital-business-cards](https://github.com/mmiller-HMC/digital-business-cards):

```bash
BASE_URL=https://mmiller-hmc.github.io/cards python3 build.py
```

QR codes here encode the **staging** URL. They must be regenerated against the
production `base_url` before anyone prints or distributes them.

`robots.txt` blocks indexing so these pages never compete with the real cards.
