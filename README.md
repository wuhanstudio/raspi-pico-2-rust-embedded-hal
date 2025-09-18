# Rust Embedded on Raspi Pico 2 (Dual Core)

## Prerequisites

Install Rust toolchain:

```
# Cortex M33 (With FPU)
$ rustup target add thumbv8m.main-none-eabihf

# Cortex M33 (Without FPU)
$ rustup target add thumbv8m.main-none-eabi

# RISC-V
$ rustup target add riscv32imac-unknown-none-elf
```

Install Probe-rs:

- https://probe.rs/docs/getting-started/installation/

Install Picotool:

- https://github.com/raspberrypi/picotool/releases

## Projects

- [hello-picotool-arm](hello-picotool-arm): Cortex-M (No debugging)  
- [hello-probe-rs-arm](hello-probe-rs-arm): Cortex-M (Debugging)  

<br />

- [hello-picotool-riscv](hello-picotool-riscv): RISC-V (No debugging)  
- [hello-probe-rs-riscv](hello-probe-rs-riscv): RISC-V (Debugging not supported)
