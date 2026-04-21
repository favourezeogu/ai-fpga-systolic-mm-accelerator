# AI-Assisted FPGA Design Space Exploration for Systolic Matrix Multiplication

## 🚀 Project Overview
This project demonstrates an end-to-end AI-assisted workflow for designing and simulating an FPGA-based systolic array accelerator. It follows the educational methodology provided by the TAMU TSI workshop, applying AI-driven research and modeling to a custom hardware engineering task.

Instead of a traditional report, this GitHub repository serves as a live, reproducible demonstration of how AI can assist in:
1. **Literature Review**
2. **Technology Parameter Extraction**
3. **Synthetic Workload Generation**
4. **Hardware Performance Simulation**
5. **Technical Article Generation**

---

## 🛠️ The Workflow (6-Step Method)
Our project is contained within a single Jupyter Notebook that executes the following steps:

* **Step 1: Literature Review** – Using Gemini 3 to summarize recent papers (2023-2026) on FPGA systolic arrays.
* **Step 2: Parameter Extraction** – Defining hardware constraints for the Xilinx Zynq UltraScale+ ZU9EG.
* **Step 3: Workload Generation** – Creating synthetic 1024x1024 matrix multiplication tasks.
* **Step 4: Performance Simulator** – An analytical model predicting GOPS and latency.
* **Step 5: AI Architect Interpretation** – AI-driven analysis of the design's efficiency and bottlenecks.
* **Step 6: Article Generation** – Auto-generating a research summary of our findings.

---

## 📊 Technical Specifications
* **Target Device:** Xilinx Zynq UltraScale+ MPSoC (ZU9EG)
* **Systolic Array Size:** 16 x 16 PEs
* **Theoretical Peak:** 128 GOPS @ 250MHz
* **Precision:** INT8

---

## 📂 Repository Structure
* `notebooks/`: Contains the core project notebook `accelerator_workflow.ipynb`.
* `requirements.txt`: Python dependencies needed to run the simulation.
* `data/`: Placeholder for exported simulation results.

---

## ⚡ How to Run
1. Open the notebook in **Google Colab**.
2. Add your `GOOGLE_API_KEY` to the Colab Secrets tab.
3. Run all cells to see the AI-assisted design process in action.

**Author:** [Your Name/Group Name]  
**Course:** Digital Communication / Advanced FPGA Design  
**Date:** April 2026
