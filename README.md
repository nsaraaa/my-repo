# 🛡️ XploitStrike

<div align="center">
    <img src="https://github.com/user-attachments/assets/c43e6ab2-5ff1-4589-9441-f7c24fce1bc7" alt="XploitStrike Logo" width="500">
    <br>
    <br>
    <strong>Advanced Penetration Testing Framework</strong>
    <br>
    <em>Automated vulnerability detection and exploitation engine</em>
</div>

## 📋 Overview

**XploitStrike** is a powerful command-line based automated penetration testing tool designed to identify and exploit vulnerabilities in web applications. The framework leverages advanced machine learning models, including neural networks and transformers, to automatically generate payloads, mutate them, and classify vulnerabilities with high accuracy.

<div align="center">
    <img src="https://github.com/user-attachments/assets/278a87e0-caca-4fd8-a499-8efa88fcb169" alt="XploitStrike Screenshot" width="650">
</div>

## ⚔️ Core Capabilities

| Module | Description |
|--------|-------------|
| **SQLi** | Extracts SQL injection payloads from vulnerable sites, mutates them, and tests them using a neural network and reinforcement learning for classification and reporting |
| **XSS** | Generates unique XSS payloads using a transformer model and classifies them with a neural network |
| **CSRF** | _(Under Development)_ Automatic detection and exploitation of Cross-Site Request Forgery vulnerabilities |
| **MITM** | Network traffic interception with real-time analysis and packet inspection |
| **DDoS** | Network stress testing simulation with configurable attack parameters |

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/nsaraaa/AutoPentesting
cd AutoPentesting

# Install dependencies
pip install -r requirements.txt
```

### Model Resources

Download the GPT Transformer model:
[Download GPT Transformer](https://www.dropbox.com/scl/fo/tiopa14tkt8yz5yy0jqel/AL5i1AZJdQoCRVac8HSPAIg?rlkey=axnxsre4l2te5iorz9bdiob03&st=qlezkcgi&dl=1)

## 🎮 Usage

### Command Line Options

```bash
python main.py [-h] [--train] [--attack] [--target TARGET] [--cookie COOKIE] [--episodes EPISODES]
```

| Option | Description |
|--------|-------------|
| `-h, --help` | Show help message and exit |
| `--train` | Train the detector model |
| `--attack` | Run adaptive attacks |
| `--target TARGET` | Specify the target URL for the attack |
| `--cookie COOKIE` | Set cookie for authenticated requests |
| `--episodes EPISODES` | Define the number of training episodes |

### Interactive Menu

XploitStrike also features an intuitive tactical menu:

1. **SQL Injection** - Database penetration testing
2. **XSS Attack** - Client-side vulnerability assessment
3. **DDoS Simulator** - Network stress testing
4. **MITM Attack** - Network traffic interception
5. **EXIT** - Terminate session

## ⚙️ System Requirements

- Python 3.8+
- Administrator privileges (required for certain network operations)
- Network access permissions

## 🛠️ Architecture

XploitStrike implements an advanced architecture with several key components:

- **Neural Network Classifiers**: For high-precision vulnerability detection
- **Transformer Models**: Generate context-aware attack payloads
- **Reinforcement Learning**: Adaptive payload mutation and optimization
- **Signal Handling**: Graceful termination and cleanup of attack processes
- **Privilege Management**: Automatic elevation of privileges when required

## 📜 License

MIT License

## ⚠️ Disclaimer

This tool is developed for educational and security testing purposes only. Use responsibly and only against systems you have permission to test.
