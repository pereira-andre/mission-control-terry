# Mission Control

A free, local-first, 16-color mission board dedicated to Terry A. Davis.

This is a single-file browser app inspired by old command surfaces and the clarity of direct tools. It stores your board in `localStorage`, runs without a backend, and can be opened directly from `index.html`.

## Features

- Three-lane mission board: `QUEUE`, `SCAN`, `DONE`
- Drag missions between lanes
- Mission editor with title, next action, priority, progress, tags, URL, and image URL
- Optional thumbnails and visible links on mission cards
- Import/export JSON
- Resizable left system rail and right terminal area
- Resizable floating windows
- Animated ASCII rail with browser-visible system/network information
- Local terminal-style command panel
- Light/night modes

## Terminal Commands

```text
help
new
edit
theme
day
night
filter all
filter queue
filter scan
filter done
brief
status
export
import
clear
```

## Data

Mission Control saves data in the browser under localStorage. Use `File > Export JSON` to keep backups or move boards between browsers.

Example mission JSON:

```json
{
  "title": "Ship the demo",
  "codename": "M-001",
  "status": "queue",
  "priority": "high",
  "progress": 35,
  "nextAction": "Record a short walkthrough",
  "referenceUrl": "https://example.com",
  "imageUrl": "https://example.com/thumbnail.jpg",
  "tags": ["demo", "launch"]
}
```

## Dedication

In memory of Terry A. Davis (1969-2018). Respect for the engineering, the directness, and the singular vision.

This project is not affiliated with TempleOS.

## License

MIT
