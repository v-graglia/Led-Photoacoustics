# Led-Photoacoustics
Designs for a LED based Photoacoustics light source


## Capabilities
 - Pulse width: 70 - 1 $\mu s$
 - Current: > 20 A
 - Energy/Pulse: up to 100 $\mu J$ @ 63 V/200 ns

## Usage
### Pin layout:

| Col 1 | Col 2 |
|:---:|:------:|
| GND | Signal |
| GND |   Vcc  |
| GND |   Vs   |
| GND | Button |

### Inputs
- Signal: TTL/CMOS  
- VCC = 10 V
- VS ≥ 50 V

## Files
The board designs are provided as is, in Eagle format.
The following files can be found in the `Files` folder:
- Gerber files, both in imperial and metric RS-274X format:
  - `gerbers_RS-274_imperial.zip`
  - `gerbers_RS-274_metric.zip`

- `photoacoustic_board.rar`, containing
  - `board.sch` - schematic file.
  - `board.brd` - board file.

- `library.lib' - Library containing all the components utilized in the schematic

- `photoacoustic_board.pdf` - PDF of the schematics.
