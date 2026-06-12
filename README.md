# IEL – Electronics for IT

Solutions to 5 circuit analysis problems completed as part of the *Electronics for Information Technology* (IEL) course at FIT VUT Brno.

Grade: **A (90/100)**

---

## Problems

### Example 1 – Circuit Simplification
Calculated voltage **U_R3** and current **I_R3** using iterative circuit simplification (series/parallel reduction + delta-to-star transformation).

Result: `U_R3 = 42.12 V`, `I_R3 = 0.0766 A`

### Example 2 – Thévenin's Theorem
Calculated voltage **U_R4** and current **I_R4** by reducing the circuit to its Thévenin equivalent (U_i, R_i).

Result: `U_R4 = 35.02 V`, `I_R4 = 0.0614 A`

### Example 3 – Node Voltage Method
Calculated voltage **U_R2** and current **I_R2** using the node voltage method with three unknown node voltages (U_A, U_B, U_C) solved via Cramer's rule.

Result: `U_R2 = 41.50 V`, `I_R2 = 1.3388 A`

### Example 4 – Mesh Current Method (AC)
Determined amplitude **|U_L1|** and phase **φ_L1** of voltage across inductor L1 in an AC circuit using the mesh current method with complex impedances.

Result: `|U_L1| = 2.767 V`, `φ_L1 = 9.71°`

### Example 5 – Differential Equation (RL Circuit)
Derived and solved the differential equation describing current i_L(t) in an RL circuit after switch closure at t = 0, including analytical solution and correctness verification.

Result: `i_L(t) = 2 + 13·e^(−5t)`

---

## Methods Used

- Series/parallel resistance reduction
- Delta-to-star (Δ→Y) transformation
- Thévenin's theorem
- Node voltage method
- Mesh current method
- Complex impedance analysis
- First-order ODE analytical solution

## Tools

- Circuit diagrams drawn manually
- Calculations done by hand with fraction arithmetic
