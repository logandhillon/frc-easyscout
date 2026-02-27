# FRC EasyScout

Internal scouting utility for FRC Team 5409.

FRC EasyScout automatically scans ScoutingPASS QR codes containing TSV match data and inputs them directly into a
spreadsheet processor — no manual copy/paste, no data entry overhead.

## What It Does

- Continuously scans all visible ScoutingPASS QR codes
- Parses embedded TSV data
- Automatically forwards structured data into your existing spreadsheet workflow
- Eliminates manual upload steps

### Why

Scouters should focus on collecting accurate match data — not managing files, tabs, or imports. This tool removes the
human step between QR scan and spreadsheet.

### Compatibility

- Designed to work with existing spreadsheet-based scouting systems
- Outputs TSV-compatible structured data
- Intended for internal team use

## Usage

Download the latest release here:

https://github.com/logandhillon/frc-easyscout/releases/latest

Once downloaded, install all dependencies (it is recommended to use a `venv`)

```shell
pip3 install -r requirements.txt
```

Finally, run the `easyscout.py` script to start the program.

```shell
python3 easyscout.py
```

---

© 2024-2026 logandhillon.com · Team 5409
