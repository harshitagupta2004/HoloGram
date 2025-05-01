# HoloGram
HoloGram: AI-powered real-time intruder detection using 3D holographic vision with monocular cameras. This lightweight system combines MediaPipe for pose detection and MiDaS for depth estimation to create pseudo-3D volumetric representations of human movement. Perfect for smart security on edge devices like Raspberry Pi. 
# HoloGuard - AI-Powered 3D Intruder Detection

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Build Status](https://github.com/yourusername/HoloGuard/actions/workflows/ci.yml/badge.svg)](https://github.com/yourusername/HoloGuard/actions)

<p align="center">
  <img src="docs/demo.gif" alt="HoloGuard Demo" width="600"/>
</p>

## 🔮 Project Overview

HoloGuard transforms standard cameras into intelligent 3D surveillance systems using:
- **Real-time pose detection** (MediaPipe BlazePose)
- **Monocular depth estimation** (MiDaS AI)
- **Holographic visualization** (OpenCV effects)

## ✨ Features

- 🕵️ Person detection with skeletal tracking
- 📏 Distance estimation from single camera
- 💻 Edge device compatible (Raspberry Pi/Jetson)
- 🌈 Customizable hologram effects

## 🚀 Quick Start

```bash
# Install with pip
pip install hologuard

# Run webcam demo
hologuard-demo
