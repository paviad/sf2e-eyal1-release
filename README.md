# SF2e Campaign: eyal1 — releases

Release packages of a Foundry VTT module with campaign-specific features for
one Starfinder 2e campaign. Currently:

- **Countdown:** a countdown to the apocalypse, in game time, shown at the top
  of every player's screen. It follows the World Clock, so it moves whenever
  the GM advances time. The GM sets it by clicking it, or from
  **Configure Settings** → this module → **Configure**.

This repository holds releases only; there is no source here.

## Install

In Foundry's **Setup** screen → **Add-on Modules** → **Install Module**, paste
this into *Manifest URL*:

```
https://github.com/paviad/sf2e-eyal1-release/releases/latest/download/module.json
```

Then enable it in the world: **Game Settings** → **Manage Modules**.

Updates appear in the Add-on Modules list — click **Update**, then relaunch
the world.

## Get notified of new versions

- **Email and phone:** on this page click **Watch** → **Custom** → tick
  **Releases** → **Apply** (needs a free GitHub account).
- **RSS, no account:** subscribe to
  `https://github.com/paviad/sf2e-eyal1-release/releases.atom`.

## Requirements

- Foundry VTT **v14**
- Game system **Starfinder 2e** (`sf2e`)
