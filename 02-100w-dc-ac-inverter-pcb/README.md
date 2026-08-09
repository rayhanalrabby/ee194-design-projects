# 100 W DC–AC Inverter — PCB Design

Design a 100 W inverter that converts DC (battery or solar) to
mains-style AC, taken from circuit research through to a
manufacturable PCB layout in EAGLE.

![Board layout](images/board-layout-routed.png)

## Approach
Started from published 100 W inverter topologies, then each of the
six of us built schematics in EAGLE independently — partly to get
everyone fluent in the tool, partly to have two or three viable
candidates to choose from rather than committing to the first idea.
The strongest schematic was carried through to board layout.

Seven weeks, split across research, schematic capture, layout,
report, and presentation.

## Files
- `schematic/` — EAGLE .sch files
- `board/` — EAGLE .brd layout
- `gerbers/` — fabrication output
- `docs/` — report and BOM

## Takeaways
- Schematic correctness and board manufacturability are separate
  problems. A circuit that simulates fine still has to survive
  trace-width, clearance, and thermal constraints on the copper.
- Mains-level output means clearance and isolation stop being
  cosmetic. Getting the high-voltage side laid out safely drove more
  of the layout decisions than component placement did.

---
EE194 Project-Based Learning, Maynooth University, Semester 1, Year 1 (2024).
Group of 6 — my contribution: [fill in: schematic design / layout /
component selection / report section].
