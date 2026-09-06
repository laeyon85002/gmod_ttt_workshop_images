# TTT2 Workshop Images

Public image host for `[img]`-Links in den Steam-Workshop-Beschreibungen der TTT2-Addons (siehe `../gmod_ttt_addon_*/workshop/description.md`). Ersetzt Imgur — kein Cookie-Consent-Zirkus beim Zugriff, keine Gefahr, dass ein Album offline geht.

Erzeugt werden alle Banner von der Icon-Pipeline in `../gmod_ttt_materials/_icon_pipeline/`
(`make_banner.py` fuer die generischen Abschnittsbanner, `icon_pipeline.py --banner-title` fuer die
Addon-Titelbanner); Ablage der Originale: `../gmod_ttt_materials/workshopvorlagen/`. Die alten
PSD/AF-Arbeitsdateien liegen dort weiterhin, werden aber nicht mehr gebraucht.

## Hotlink-Schema

```
https://raw.githubusercontent.com/laeyon85002/gmod_ttt_workshop_images/main/<datei>.png
```

## Dateien

- `workshopDescription_features.png` — generisches "Features"-Section-Banner
- `workshopDescription_requirements.png` — generisches "Requirements"-Section-Banner
- `workshopDescription_credits.png` — generisches "Credits"-Section-Banner
- `workshopDescription_convars.png` — generisches "ConVars"/"Server-ConVars"-Section-Banner
- `workshopDescription_stimPistol.png` — Titelbanner für Stim Pistol
- `workshopDescription_rolechangerdeagle.png` — Titelbanner für Role Changer Deagle
- `workshopDescription_toxicSmokeGrenade.png` — Titelbanner für Toxic Smoke Grenade
- `workshopDescription_chaosGrenade.png` — Titelbanner für Chaos Grenade
- `workshopDescription_suspectRadar.png` — Titelbanner für Suspect Radar

Alle Banner werden aktuell in mindestens einer Addon-Description eingesetzt. Stand 2026-09-06:
vollständig, keine offenen Lücken. An diesem Tag wurden sämtliche Banner aus der Pipeline neu
erzeugt, damit Schrift und Kasten über alle Addons hinweg identisch sind.
