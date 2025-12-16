# Gesture Controlled 3D Particle System

An interactive 3D particle system built with **Three.js** and **MediaPipe Hands**.  
Your webcam tracks hand gestures in real time to control particle behavior:

- ✋ **Expansion** → Thumb–index distance controls particle spread & size  
- 👆 **Color** → Vertical index finger movement changes particle hue  
- 🔀 **Templates** → Switch between particle shapes:
  - ✌ Two fingers → Heart
  - 🤟 Three fingers → Flower
  - 🖖 Four fingers → Saturn
  - 🖐 Five fingers → Fireworks
  - 👊 Fist / other → Sphere

---

## 🚀 Features
- Real‑time hand tracking via MediaPipe Hands
- Dynamic particle templates (sphere, heart, flower, Saturn, fireworks)
- Smooth gesture‑based controls for expansion and color
- Lightweight rendering with Three.js `PointsMaterial`
- Responsive design with auto‑resize

---

## 📦 Installation

1. Clone or download this repository.
   ```bash
   git clone https://github.com/yourusername/gesture-particles.git
   cd gesture-particles
