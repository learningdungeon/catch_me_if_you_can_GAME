# catch_me_if_you_can_GAME
 Quantum educational game hunt the electron using Schrödinger's wave function. Built for unitaryHACK 2026.
# 🌊 Ripple: The Electron Heist

**A quantum educational game teaching Schrödinger's wave function, measurement collapse, and the uncertainty principle.**

Built for unitaryHACK 2026 | Created by Noor Ul Ain Faisal

---

## 🎮 About the Game

The electron is not a marble. It's a **wave of probability**.

You are a quantum spy. Your target: an electron carrying a secret message through a quantum wire. But this electron has no exact position — it's a Schrödinger wave function, spread across space as a probability cloud.

You have limited measurement probes. Each probe collapses the wave near where you click — but never exactly at the electron's true position. Probe too much? The electron escapes.

**Find it before your probes run out.**

---

## 🧠 Quantum Concepts Taught

| Concept | How the Game Teaches It |
|---------|------------------------|
| **Schrödinger's Wave Function (ψ)** | The electron is displayed as a probability distribution, not a dot |
| **Probability Density (|ψ|²)** | Clicking shows your probability of finding it there |
| **Measurement Collapse** | Each probe narrows the wave — you create the result by looking |
| **Uncertainty Principle** | Too many measurements disturb the system — the electron escapes |
| **Quantum Security** | This is why Eve can't intercept without leaving a trace |

---

## 🎯 How to Play

1. Open the notebook in Google Colab
2. Click **📚 What is the Wave?** to learn the physics
3. Click any **Pos** button to probe the wave
4. Use the probability feedback to narrow your search
5. Find the electron within 0.3 units to catch it
6. Three levels of increasing difficulty

---

## 🏆 Levels

| Level | Wave Width | Probes | Difficulty |
|-------|------------|--------|------------|
| 1 | Wide (2.5) | 5 | The electron is spread out. Easier to find. |
| 2 | Medium (1.5) | 4 | Narrower wave. Fewer chances. |
| 3 | Narrow (0.8) | 3 | Expert mode. The uncertainty principle is your enemy. |

---

## 📦 Dependencies

- Python 3.7+
- `numpy`
- `ipywidgets`

Install: `pip install numpy ipywidgets`

Runs on Google Colab — no local setup required.

---

## 🔬 Connection to Real Quantum Physics

This game is built on the **Schrödinger equation**, the foundation of quantum mechanics:

**iℏ ∂ψ/∂t = - (ℏ²/2m) ∂²ψ/∂x² + V(x)ψ**

Before measurement, the electron has no definite position — it exists as a superposition of all possible positions. The wave function ψ encodes the probability of finding it anywhere.

**Measurement collapses the wave.** This is not a game mechanic. This is physics.

In quantum networks like **RAQT** and **BB84**, this principle guarantees security. An eavesdropper who measures a qubit disturbs its wave function. The disturbance is detectable. Physics protects the message.

---

## 👤 About the Creator

I am Noor Ul Ain Faisal — an independent quantum researcher from Sialkot, Pakistan.

I came to quantum computing through an unconventional path. I hold an MA in English Literature. I couldn't study sciences when I was young. Years later, I returned to my passion. I taught myself quantum mechanics from MIT OCW 8.04 and Stanford Online. I learned Python, Qiskit, and NetSquid on my own.

**Today:**
- IBM Qiskit Advocate (2025)
- Friend of OQI, Open Quantum Institute at CERN (2026)
- Member, IEEE GRSS QUEST Technical Committee
- Mentor, Qiskit Advocate Mentorship Program (QAMP)
- Only participant from Pakistan to pass IBM QGSS
- Developer of RAQT quantum network protocol

**My other quantum game:** [Elliot the Electron — BB84 & No-Cloning Theorem](https://github.com/learningdungeon/Quantum-Universal-Education.github.io/tree/master/UNITARYHACK/quantum-spy-elliot-bb84-game)

---

## 🤖 AI Usage Disclosure

- **AI Tool Used:** DeepSeek
- **AI Assistance:** Code structure, HTML/CSS styling, and markdown formatting
- **Human-Created:** Game concept, quantum physics explanations, wave function visualization design, educational structure, and all physics content are my original work. All code manually tested and verified on Google Colab.

---

## 📄 License

MIT License

---

*"The electron is not a marble. It's a wave. Catch it... if you can."* — 🌊
