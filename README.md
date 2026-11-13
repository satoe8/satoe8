# Hi, I'm Elliott

Electrical Engineering @ Purdue University ('28). I build digital chips, avionics, and low-latency drivers.

## Featured Work

### CoreMux SDK — Hardware-Accelerated Video Transport
Windows-to-iOS low-latency display extension and video transport SDK (`CoreMuxHost.dll` + `CoreMuxClient`)
- **Stack:** C++20, Windows IddCx (UMDF 2.x), Direct3D 11 / DXGI, NVIDIA NVENC, Swift, Metal, Core ML
- **Architecture:** Extracted a Windows Indirect Display Driver and DXGI capture pipeline into a standalone C-ABI dynamic library (`CoreMuxHost.dll`) paired with a Swift/Metal iOS client over LAN and native USB (`usbmuxd`).
- **Performance:** Achieved 1.6–8.5 ms H.264 encode latency using direct `nvEncodeAPI` with per-macroblock delta-QP region-of-interest (ROI) bit allocation, paired with an FP16 Core ML super-resolution upscaler running on the Apple Neural Engine (14–21 ms).

### [AMBA APB4 UVM Verification IP](https://github.com/satoe8/AMBA-APB-Protocol-UVM-Verification-IP)
Reusable, self-checking UVM 1.2 environment validating an AMBA APB4 bus bridge
- **Stack:** SystemVerilog, UVM 1.2, SystemVerilog Assertions (SVA), Siemens QuestaSim, Linux/Bash
- **Highlights:** Built master/slave agents, a passive monitor, a TLM scoreboard with a golden register-file reference model, and 12 concurrent SVA protocol checks—reaching 100% functional coverage via constrained-random stimulus.

### [ASTRA Satellite Telemetry Architecture](https://github.com/Purdue-SoCET/intro2_S2026_Telemetry_tt)
CCSDS-compliant telemetry packetizer for the Purdue SoCET VIP Telemetry SoC
- **Stack:** SystemVerilog, Artix-7 FPGA, Vivado, Cadence Virtuoso
- **Highlights:** Served as Lead RTL Designer, implementing a 10-state Gray-coded FSM and fault-tolerant data paths verified on Artix-7 FPGA fabric through the Purdue STARS semiconductor program.

### Avionics & Servo Control — Purdue IEEE AESS (DAVE Supersonic UAV)
- **Stack:** MATLAB, KiCad, C++, SPI (AS5048A Magnetic Encoders), Embedded DAQ
- **Highlights:** Hardware Integration Lead directing avionics layout, flight controller integration, and closed-loop actuator transfer function modeling for a small supersonic UAV prototype.

### Open-Source Silicon Verification — OpenTitan
- **Stack:** SystemVerilog, UVM, Verilator / VCS
- **Highlights:** Debugging and validating UVM driver and monitor handshake sequences for security-critical open-source silicon IP modules.

### [Hardware-Accelerated Quick Sort](https://github.com/satoe8/hardware-accelerated-sorting)
Cycle-accurate comparison of a Verilog hardware sorting engine vs. RISC-V assembly and C baselines
- **Stack:** Verilog, RISC-V Assembly, C++, Verilator
- **Highlights:** Achieved a 75–121× speedup over software baselines through custom FSM and datapath design.

## Skills
- **Silicon & Verification:** SystemVerilog, Verilog, UVM 1.2, SVA, AMBA APB, RISC-V, Siemens QuestaSim, Vivado, Verilator, Cadence Virtuoso
- **Avionics & Embedded:** KiCad PCB Design, SPI/I2C, MATLAB Control Modeling, Oscilloscope & Logic Analyzer Bring-up
- **Systems & Graphics:** C, C++, Rust, Python, Windows UMDF 2.x (IddCx), Direct3D 11 / DXGI, NVENC, Swift, Metal, Core ML

## Outside the Lab
Club ice hockey @ Purdue and classical cello.

## Contact
- **Email:** satoe@purdue.edu
- **LinkedIn:** [linkedin.com/in/elliottsato](https://linkedin.com/in/elliottsato)
