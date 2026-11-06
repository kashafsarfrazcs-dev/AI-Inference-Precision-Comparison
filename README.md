# Numerical Precision Impact on AI Inference Across CPU, GPU, TPU and NPU

## Computer Architecture — Individual Research Project

### Project Overview
This research investigates how numerical precision affects AI performance across different computing architectures. It compares CPU, GPU, and TPU using matrix multiplication, memory bandwidth, numerical precision benchmarks, AI inference workloads, and performance analysis.

**Note:** NPU was included in the research scope, but no NPU hardware was available for experimental testing.

### Objectives
- Compare CPU, GPU, and TPU performance.
- Study the impact of FP32, FP16, and BF16 numerical precision.
- Measure matrix multiplication performance and memory bandwidth.
- Evaluate AI inference workloads.
- Analyze performance using Roofline Model, Amdahl's Law, and CPU performance profiling.

### Experimental Environment
- Platform: Google Colab
- CPU: Intel Xeon CPU
- GPU: NVIDIA Tesla T4
- TPU: Google Cloud TPU v5e-1
- Framework: PyTorch

### AI Workloads
- ResNet-50 — CNN workload
- DistilBERT — Transformer workload
- LSTM — Sequential workload
- FashionMNIST CNN — Training experiment

### Repository Structure
- `01_Research_Paper/` — Research paper
- `02_Presentation/` — Presentation slides
- `03_Code/` — Experimental notebook
- `04_Results/` — CSV datasets and graphs
- `05_Documentation/` — Supporting documentation

### Performance Analysis
The project includes:
- Matrix multiplication benchmarks
- Memory bandwidth measurements
- Numerical precision comparison
- AI inference performance
- Roofline analysis
- Amdahl's Law analysis
- CPU thread-scaling experiment

### Reproducibility
The experimental notebook and result files are provided for reviewing the methodology and measured results. Hardware availability and runtime limitations may affect reproduction.

### Limitations
- NPU hardware was unavailable for testing.
- TPU testing was affected by Colab runtime availability and usage limits.
- Results should be interpreted in the context of the tested hardware and software environment.

### Academic Project
Computer Architecture — FAST National University of Computer and Emerging Sciences, Faisalabad Campus.

