<div align="center">

# <img src="https://img.icons8.com/color/48/processor.png" width="32"/> GPU vs CPU vs TPU Simulator

### Interactive AI Processing Performance Comparison

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=for-the-badge&logo=vercel)](https://gpu-cpu-tpu-simulator.vercel.app)
[![GitHub Pages](https://img.shields.io/badge/github-pages-blue?style=for-the-badge&logo=github)](https://romizone.github.io/gpu-cpu-tpu-simulator/)
[![Release](https://img.shields.io/github/v/release/romizone/gpu-cpu-tpu-simulator?style=for-the-badge&color=orange)](https://github.com/romizone/gpu-cpu-tpu-simulator/releases)
[![License](https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge)](LICENSE)

<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/No_Dependencies-4CAF50?style=flat-square"/>

<br/><br/>

> A real-time visual simulator that demonstrates the dramatic performance differences between **CPU**, **GPU**, and **TPU** when processing AI & deep learning workloads.

<br/>

</div>

---

## Features

| Feature | Description |
|---------|-------------|
| **Processing Race** | Real-time race lanes showing speed differences visually |
| **Global Timer** | Millisecond-precision elapsed timer |
| **Status Badges** | IDLE / RUNNING (pulse) / FINISHED indicators |
| **Timestamps** | Start time, elapsed, and finish time per processor |
| **Core Animation** | Smooth pulse animation on active cores |
| **Time Comparison** | Dramatic speedup visualization (e.g. 65x faster) |
| **Multiple Workloads** | Matrix Multiply, CNN Training, Inference, NLP Transformer |
| **Architecture Diagrams** | ASCII art of CPU, GPU, TPU internal architecture |

## Workloads

| Workload | Description | CPU | GPU | TPU |
|----------|-------------|:---:|:---:|:---:|
| **Matrix Multiplication** | 1024x1024 matrix ops | 1x | 45x | 65x |
| **CNN Training** | ResNet-50, 1 epoch | 1x | 55x | 70x |
| **Batch Inference** | Image classification | 1x | 35x | 80x |
| **NLP Transformer** | BERT-Base | 1x | 50x | 75x |

## Processor Specs (Simulated)

<table>
<tr>
<td align="center"><strong>CPU</strong><br/><sub>8 Cores / 16 Threads<br/>5.0 GHz<br/>Sequential Processing</sub></td>
<td align="center"><strong>GPU</strong><br/><sub>4096 CUDA Cores<br/>1.8 GHz<br/>Massive Parallelism</sub></td>
<td align="center"><strong>TPU</strong><br/><sub>128x128 Systolic Array<br/>940 MHz<br/>Tensor Optimized</sub></td>
</tr>
</table>

## Quick Start

No build step required. Just open `index.html` in a browser.

```bash
# Clone
git clone https://github.com/romizone/gpu-cpu-tpu-simulator.git
cd gpu-cpu-tpu-simulator

# Open directly
open index.html

# Or serve locally
npx serve -p 3456
```

## Deploy

| Platform | Status |
|----------|--------|
| **GitHub Pages** | Auto-deploy on push to `main` |
| **Vercel** | Connected to GitHub repo |

## Tech Stack

- **Zero dependencies** — Pure HTML, CSS, JavaScript
- **Single file** — Everything in `index.html`
- **No build process** — Open and run
- **Responsive** — Works on desktop & mobile

## License

MIT

---

<div align="center">

**[Live Demo](https://gpu-cpu-tpu-simulator.vercel.app)** · **[GitHub Pages](https://romizone.github.io/gpu-cpu-tpu-simulator/)** · **[Report Bug](https://github.com/romizone/gpu-cpu-tpu-simulator/issues)**

</div>
