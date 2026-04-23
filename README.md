# OTA-Design-project
Design project of OTA (Operational Transconductance Amplifier) in 45 nm CMOS Technology using Cadence Virtuoso. 
Design was verified by various simulations using different testbenches. Group project (2 people).


## Design Specifications and Results

| Parameter | Target | Result |
|----------|--------|--------|
| Supply Voltage (Vdd) | 3 V | 3V |
| Gain (A) | > 39 dB (≈ > 90 V/V) | 40.5 dB |
| Unity Gain Bandwidth (ft) | > 10 MHz | 11.4 MHz |
| Slew Rate (SR) | > 10 MV/s | 15 MV/s |
| Phase Margin (PM) | > 60° | 103° |
| Output Linear Range | 0.6 – 2.2 V | 0.48 V - 2.3 V |
| Input Common-Mode Range | 1.5 – 2.3 V | 0.9 V - 1.9 V |
| Current Ratio (K) | 2 | 2 |

## Schematics
### OTA
![OTA_schematic](OTA_schematic.png)

### Testbench for DC-simulations
![TB_DC](testbench_dc.png)

### Testbench for AC-simulations
![TB_AC](testbench_ac_bode.png)
