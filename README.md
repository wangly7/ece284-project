# CNN Systolic Array Accelerator

A hardware/software co-design project for efficient CNN inference on FPGA, featuring quantization-aware training, versatile pruning, and reconfigurable 2-D systolic array architectures.

---

## Features

- Quantization-aware training (2-bit / 4-bit)
- Coarse-to-Fine pruning
- 8×8 Weight-Stationary systolic array
- WS/OS reconfigurable architecture
- 2-bit / 4-bit SIMD processing elements
- Multi-core tiling
- Output-Stationary skip optimization
- FPGA implementation on Cyclone IV GX

---

## Hardware

- Weight-Stationary (WS)
- Output-Stationary (OS)
- 8×8 Processing Element Array
- Reconfigurable SIMD PE
- FIFO-based dataflow
- Clock gating
- Multi-core tiling

---

## Software

- CIFAR-10 training
- Quantization-aware training
- Coarse-to-Fine pruning
- Adam
- Label Smoothing
- Cosine Scheduler

---

## Results

| Metric | Value |
|--------|------:|
| FPGA | Cyclone IV GX |
| Frequency | 128.72 MHz |
| Throughput | 16.5 GOP/s |
| Energy Efficiency | 48.4 GOP/W |
| Logic Utilization | 11% |

---

## Tech Stack

Verilog • FPGA • Quartus • Python • PyTorch • CNN • VLSI

