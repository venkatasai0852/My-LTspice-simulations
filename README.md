# ⚡ LTspice Analog Design

> *A structured exploration of analog electronics through simulation, analysis, and engineering validation.*

---

## 🔗 Repository

👉 https://github.com/venkatasai0852/My-LTspice-simulations

---

## 🎯 Purpose

This repository is not just a collection of circuits — it is a **systematic study of analog design principles** using LTspice.

Focus areas:

* Gain vs Bandwidth Tradeoff
* Feedback & Stability
* Linearity vs Efficiency
* Biasing & Operating Point Control
* Practical Non-Ideal Effects

📌 Each circuit is simulated to **validate theory with real behavior**.

---

## 🧠 Skills Demonstrated

* Small-signal & large-signal analysis
* Frequency response & Bode plots
* Feedback topology understanding
* Oscillator design & amplitude stabilization
* Biasing techniques
* Circuit debugging using simulation

---

## 🔬 Simulation Domains

---

### 🔊 Amplifiers

* Single-stage CE amplifier
* Two-stage RC-coupled amplifier
* Emitter follower (voltage follower)

📊 **Insights:**

* Gain vs linearity tradeoff
* Loading effects in cascaded stages
* Impedance transformation

---

### ⚡ Power Amplifiers

* Class A
* Class B (Push-Pull)
* Class AB

📊 **Insights:**

* Crossover distortion in Class B
* Efficiency vs linearity tradeoff
* Biasing impact in Class AB

---

### 🔁 Feedback Topologies (All 4 Types)

* Current-Series Feedback
* Current-Shunt Feedback
* Voltage-Series Feedback
* Voltage-Shunt Feedback

📊 **Insights:**

* Gain reduction improves stability
* Bandwidth increases in voltage-series feedback
* Input/output resistance variation
* Closed-loop vs open-loop behavior

---

### 🌀 Oscillators (Op-Amp Based)

#### RC Phase Shift Oscillator

* 3-stage RC network
* Phase shift-based oscillation

#### Wien Bridge Oscillator

* Frequency-selective bridge
* **Automatic amplitude stabilization using diode limiter (AGC)**

📊 **Insights:**

* Barkhausen criterion verified
* Amplitude stabilization via nonlinear control
* Frequency matches theoretical predictions

---

### 🪞 Current Mirrors & Differential Circuits

* BJT Current Mirror
* Differential Amplifier

📊 **Insights:**

* Constant current biasing
* Effect of transistor mismatch
* Differential vs common-mode behavior (CMRR)

---

### ⚡ Rectifiers & Filters

* Half-wave rectifier with RC filter
* Parametric sweep (capacitor variation)

📊 **Insights:**

* Ripple vs capacitance tradeoff
* Charging/discharging waveform behavior

---

### 💻 CMOS / VLSI Basics

* NMOS switching circuits
* Basic CMOS logic

📊 **Insights:**

* Switching thresholds
* Transient response

---

## 📈 Representative Simulation Studies

* Frequency response & -3 dB bandwidth
* Transient waveform analysis
* Parametric sweeps
* Operating point (.op) validation
* Stability vs gain tradeoff

---

## 🧪 Design Review & Engineering Validation

Each circuit is critically analyzed beyond simulation.

### 🔍 Evaluations Performed

* Q-point stability
* Gain vs theoretical comparison
* Bandwidth limitations
* Component sensitivity
* Non-linear distortion
* Inter-stage loading effects

---

### 📊 Key Observations

* CE amplifier gain deviates due to loading
* Class B shows crossover distortion
* Feedback improves bandwidth but reduces gain
* Wien bridge stabilizes amplitude via diode conduction
* RC oscillator startup depends on loop gain

---

### ⚠️ Practical Learnings

* Ideal theory ≠ practical results
* Biasing is critical
* Parasitics affect frequency response
* Feedback improves robustness

---

## 🛠️ Tools Used

* LTspice XVII (Analog Devices)

---

## ▶️ How to Run

```bash
git clone https://github.com/venkatasai0852/My-LTspice-simulations.git
```

1. Open `.asc` file
2. Click **Run ▶**
3. Probe nodes

---

## 📄 File Types

* `.asc` → schematic
* `.raw` → waveform data
* `.log` → logs
* `.plt` → plots
* `.pdf` → exports

---

## 🚧 Future Work

* MOSFET Amplifiers (CS, CD, CG)
* Active Filters
* Op-Amp Circuits
* LC Oscillators
* Noise & Distortion Analysis

---

## 👤 About

**Thota Venkata Sai**
B.Tech ECE — SVNIT Surat

🔗 https://github.com/venkatasai0852

---

## ⭐ Final Note

This repository reflects a **hands-on, engineering-first approach to analog electronics**, where theory is continuously validated through simulation.

⭐ *Star the repo to follow future updates!*
