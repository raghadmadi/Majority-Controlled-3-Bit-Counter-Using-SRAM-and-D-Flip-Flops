# Majority-Controlled 3-Bit Counter Using SRAM and D Flip-Flops

## 1) Project Overview
This project implements a **majority-controlled 3-bit counter** at the transistor and gate level.  
The counter increments **only when a majority condition is satisfied**, meaning at least **two out of three inputs are logic high**.

The system is designed and verified through **schematic design, layout design, and simulation**, following full digital IC design methodology.

This project was developed as part of the **Digital Electronics Laboratory** course.

---

## 2) System Description
- Three **6T SRAM cells** store binary inputs.
- **D flip-flops** synchronize the stored values using a shared clock.
- A **majority logic circuit** determines whether at least two inputs are high.
- A **3-bit counter** increments only when the majority condition is met.
- If the majority condition is not satisfied, the counter holds its value.

---

## 3) Key Concepts Covered
- CMOS logic design
- Transistor-level circuit implementation
- Majority logic
- Memory cells (6T SRAM)
- Clocked storage elements (D Flip-Flops, SR Latch)
- Counters and sequential logic
- Propagation delay analysis
- Schematic & layout verification

---

## 4) Components Implemented
Each component was designed, tested, and verified individually before system integration:

- CMOS Inverter  
- 2-Input NAND Gate  
- 2-Input AND Gate  
- 2-Input NOR Gate  
- 3-Input NOR Gate  
- 2-Input XOR Gate  
- Majority Logic Circuit  
- Clocked SR Latch  
- D Flip-Flop  
- 6T SRAM Cell  
- 3-Bit Counter  
- Top-Level Integrated Circuit  

---

## 5) Testing & Verification
The system was tested under multiple scenarios, including:
- All inputs = 0 (no increment)
- All inputs = 1 (counter increments to maximum)
- One input high, others low (no increment)
- Two inputs agree temporarily
- All inputs change dynamically

Waveform analysis and propagation delay measurements were used to verify correctness and timing behavior.

---

## 6) Timing Analysis
Propagation delays were measured for:
- Logic gates
- Majority circuit
- Flip-flops
- Counter outputs (Q0, Q1, Q2)

This analysis highlights the effect of timing on sequential digital systems.

---

## 7) Tools & Technologies
- CMOS Transistor-Level Design
- Schematic Design
- Layout Design
- Digital Simulation & Waveform Analysis

---

## 8) Contributors
- **Raghad Almade**  
- Batool Adawi  
- Sarah Shaheen  

Department of Computer Engineering  
The University of Jordan

---

## 9) Course Information
- **Course**: Digital Electronics Laboratory  
- **Academic Year**: 2024 / 2025  
- **Instructor**: Eng. Abeer Awad  

---

## 10) Learning Outcomes
This project strengthened understanding of:
- Translating digital theory into physical circuit designs
- Designing reliable sequential systems
- Importance of synchronization and timing
- Verification at both schematic and layout levels
