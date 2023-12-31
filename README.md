# 🍊Orenge - Open Reporting for Engineering
An open standard for reporting of building and infrastructure engineering design.

## Purpose
The purpose of this standard is to allow engineering software to share information between them and to allow more straightforward compilation and review of design reports.

## Principles
1. Be readable in raw format.
2. Allow software to extract information efficiently from the reports.
3. Allow links between different calculations.
4. Allow software to save all file information into report.

## File format
Files written with the Orenge standard are to have the file extension `.orenge`. A compiled report containing multiple `.orenge` files is to have the file extension `.corenge`.

## Dependencies
Uses the following technologies:

### Typography
- [Obsidian Markdown specification](https://help.obsidian.md/Editing+and+formatting/Obsidian+Flavored+Markdown)
- [MathJax](https://www.mathjax.org/)

### Diagramming
- [Mermaid](https://mermaid.js.org/)

### Charts
- [Chart.js](https://www.chartjs.org/)

## Roadmap
1. Release standard.
2. Create libraries for extracting information from documents.
3. Create tool for viewing and modifying documents.

## Licensing
Orenge is licensed under [GPL 3.0](LICENSE).
