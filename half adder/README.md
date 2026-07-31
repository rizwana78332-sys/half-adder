# Half Adder using Verilog

## Overview
A Half Adder is a combinational logic circuit that adds two single-bit binary numbers. It has two inputs and two outputs.

- **Inputs:** A, B
- **Outputs:**
  - Sum (S)
  - Carry (C)

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |

## Logic Equations

- Sum = A XOR B
- Carry = A AND B

## Files

- `half_adder.v` – Verilog design
- `half_adder_tb.v` – Testbench
- `waveform.png` – Simulation waveform
- `output.txt` – Simulation console output

## Simulation Tools

- ModelSim
- Icarus Verilog
- GTKWave
- Vivado

## Expected Output

```
A=0 B=0 Sum=0 Carry=0
A=0 B=1 Sum=1 Carry=0
A=1 B=0 Sum=1 Carry=0
A=1 B=1 Sum=0 Carry=1
```

## Author

Your Name
