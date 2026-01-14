# P2P Digital Communication System Simulator

<div align="center">

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/PyScript-2024.8.2-yellow.svg)

**A visual, interactive simulator for understanding digital communication pipelines**

*B.Sc Semester-V Project*

</div>

--- 
## Visit 👇
[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Now-brightgreen?style=for-the-badge&logo=github)](https://mrxtrar.github.io/p2p)

## 🎯 Overview

This web-based simulator demonstrates the complete digital communication pipeline from message transmission to reception. It visualizes how data flows through encoding, modulation, noisy channels, demodulation, and decoding stages.

## ✨ Features

- **Real-time Visualization** - Watch data flow through the communication pipeline
- **Multiple Modulation Schemes** - BPSK, QPSK, 16-QAM, 64-QAM, 256-QAM, 1024-QAM
- **Error Detection** - CRC-16, CRC-32, and Parity Bit implementations
- **Noise Simulation** - Adjustable SNR (Signal-to-Noise Ratio) with AWGN channel
- **Framing Protocols** - HDLC Flag and Length Header options
- **ARQ Protocols** - Stop-and-Wait and Selective Repeat

## 🖥️ Screenshots

<div align="center">
<img src="images/app.png" width="100" alt="Application Layer">
<img src="images/enc.png" width="100" alt="Encoding">
<img src="images/mod.png" width="100" alt="Modulation">
<img src="images/chan.png" width="100" alt="Channel">
<img src="images/dem.png" width="100" alt="Demodulation">
<img src="images/dec.png" width="100" alt="Decoding">
</div>

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for PyScript CDN)

### Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/p2p-digital-comm-simulator.git
   ```

2. Navigate to the project folder:
   ```bash
   cd p2p-digital-comm-simulator
   ```

3. Open `index.html` in your browser, or serve with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

4. Visit `http://localhost:8000` in your browser

## 📁 Project Structure

```
p2p-digital-comm-simulator/
├── index.html          # Main application file
├── images/             # Node illustration images
│   ├── app.png         # Application layer icon
│   ├── enc.png         # Encoding icon
│   ├── mod.png         # Modulation icon
│   ├── chan.png        # Channel icon
│   ├── dem.png         # Demodulation icon
│   └── dec.png         # Decoding icon
└── README.md           # This file
```

## 🔧 Technology Stack

- **Frontend**: HTML5, CSS3 (Vanilla)
- **Logic**: Python (via PyScript)
- **Math Library**: NumPy
- **Fonts**: Space Grotesk, JetBrains Mono
- **Icons**: Font Awesome

## 📚 Communication Pipeline Stages

| Stage | Description |
|-------|-------------|
| **APP** | Application layer - User inputs the message |
| **ENC** | Encoding - Converts text to binary, adds error detection |
| **MOD** | Modulation - Maps bits to complex symbols |
| **CHAN** | Channel - Simulates transmission with AWGN noise |
| **DEM** | Demodulation - Recovers symbols from noisy signal |
| **DEC** | Decoding - Verifies integrity and decodes message |

## 🎛️ Configuration Options

### Modulation Schemes
- **BPSK** - 1 bit/symbol (most robust)
- **QPSK** - 2 bits/symbol
- **16-QAM** - 4 bits/symbol
- **64-QAM** - 6 bits/symbol
- **256-QAM** - 8 bits/symbol
- **1024-QAM** - 10 bits/symbol (highest throughput)

### SNR Range
Adjustable from 0 dB to 50 dB. Lower SNR = more noise = higher error probability.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests


## 👨‍💻 Author

- B.Sc Computer Science, Semester V
- Project Year: 2026

---

<div align="center">

Made with ❤️ for educational purposes

</div>







