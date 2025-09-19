# Microwatt Security Extension – Hardware Hash & Digital Signature Verification

## Module overview

This project extends the Microwatt POWER CPU core with security-oriented functionality, progressing through a three-stage roadmap:

1.  _Custom Hash Instruction_ (MVP for hackathon demo)
2.  _Hardware Hash Accelerator_ (block-level, faster + practical)
3.  _Digital Signature Verification_ for Message Authentication (real-world crypto application)

This evolution takes the project from a simple proof-of-concept to a practical hardware accelerator and finally to an applied security solution.

The work is developed within the OpenFrame _User Project (UP)_ area, demonstrating how open-source CPUs can be customized for trust, integrity.

### Motivation

Modern computing relies fundamentally on hashing and digital signatures for:

- Verifying software integrity (e.g., secure boot)
- Ensuring message authenticity (digital signatures, HMAC)
- Enabling cryptographic applications (blockchains, secure communication)

By implementing these primitives in hardware, we can achieve:

- _Faster performance_ than software-only approaches
- _Stronger security_ primitives at the CPU level
- A clear _demonstration_ of how open CPUs like Microwatt can evolve to meet future secure computing needs

## Designing

### Stage 1: Custom Hash Instruction (MVP)

- _Goal:_ Implement a simple, custom CPU instruction to calculate a hash on a small data input stored in registers
- _Purpose:_ MVP for hackathon demo, proving the concept of extending Microwatt's ISA for security operations
- _Status:_ Planned / In Progress

### Stage 2: Hardware Hash Accelerator

- _Goal:_ Develop a dedicated hardware peripheral for high-performance hashing of large data blocks
- _Purpose:_ Practical, high-speed accelerator that significantly outperforms software implementations
- _Status:_ Planned

### Stage 3: Digital Signature Verification

- _Goal:_ Integrate a digital signature verification engine that leverages the hardware hash accelerator
- _Purpose:_ Real-world applied security application for message and code authentication
- _Status:_ Planned

## Building
--To be completed

## Contributing
--To be completed

## License
This project is licensed under MIT License - see the [Project LICENSE](https://github.com/tarique-arch/micro_HW/blob/main/Project%20LICENSE) file for details.


