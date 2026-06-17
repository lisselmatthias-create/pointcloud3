# RD Dual Pointcloud iPad

GitHub-Pages-Paket fuer die iPad-optimierte Version von `rd-audio-synth Kopie.html`.

## Dateien

- `index.html` ist die startbare Webseite.
- `.nojekyll` verhindert Jekyll-Verarbeitung bei GitHub Pages.
- `README.md` ist diese Kurznotiz.

## Was optimiert wurde

- Startet direkt im Dual-Pointcloud-Modus.
- MP3/M4A/AAC/WAV und MP4/MOV/M4V/WebM sind in den File-Pickern explizit erlaubt.
- iPad-freundlicher Start: 256er Simulation, 2 Sim-Steps, DPR 1.5, Pointcloud-Dichte 96 + 64.
- Touch/Orbit nutzt Pointer Events mit Capture.
- Safe-Area, `100dvh`, kein horizontaler Mobile-Overflow.
- Recording waehlt auf Apple-Touch-Geraeten zuerst MP4-MIME-Typen, falls Safari sie anbietet.

## GitHub Pages

1. Neues Repository auf GitHub erstellen.
2. `index.html`, `.nojekyll` und `README.md` hochladen.
3. `Settings` -> `Pages`.
4. Source: `Deploy from a branch`.
5. Branch: `main`, Ordner: `/root`.
6. Speichern und die angezeigte Pages-URL testen.

## Hinweis zu iPad-Dateien

Grosse MP4-Dateien koennen viel Speicher ziehen. Starte zum Test mit kuerzeren Clips und aktiviere erst danach hoehere Dichten oder 512er Simulation.
