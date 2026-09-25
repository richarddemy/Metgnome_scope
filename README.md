# MET Gnome Scope Lab

Experimental browser prototype for comparing a reference music signal with live microphone input.

## What it includes

- Arban/OpenArban MusicXML exercises embedded in the page
- Mode A: direct XY waveform scope
- Mode B: I/Q comparison experiment
- Selectable microphone filters
- MIDI-ish/reference synthesizer playback
- Tempo and display controls
- Explicit microphone-start button

## Phone testing

The microphone API requires a secure context. GitHub Pages serves the prototype over HTTPS, which allows Chrome/Edge/Safari to request microphone permission.

After Pages is enabled, open the Pages URL on the phone, press **Start microphone**, and allow microphone access.

## GitHub Pages

This repository includes a Pages workflow in `.github/workflows/pages.yml`.

If GitHub does not publish automatically, open **Settings → Pages** in the repository and set **Source** to **GitHub Actions**.
