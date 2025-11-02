# AIR-FOIL-PROJECT ✈️

## 📌 Project Overview
This project aims to analyze and optimize **airfoil aerodynamic performance** using a **Diffusion Model**.  
The diffusion model learns the shape distribution of airfoils and generates new airfoil geometries that may offer improved lift-to-drag ratios.

## 🎯 Objectives
- Study aerodynamic characteristics of NACA / custom airfoils
- Train a diffusion model on a dataset of airfoil geometries
- Generate *new* airfoil shapes that improve aerodynamic efficiency
- Validate generated airfoils using CFD simulations (e.g., XFoil / OpenFOAM)

---

## 🧠 Methodology

### 1. Dataset
We use an airfoil coordinate dataset (e.g., **UIUC Airfoil Database** or custom).
Each airfoil is represented as a set of `(x, y)` boundary coordinates.

### 2. Diffusion Model
- Input: Airfoil shape coordinates
- Model learns how to gradually **add noise** and **denoise** back to a valid geometry
- Output: New realistic airfoil shapes

### 3. Performance Evaluation
For each generated airfoil:
- Compute **Lift Coefficient (Cl)**
- Compute **Drag Coefficient (Cd)**
- Compute **Lift-to-Drag Ratio (Cl/Cd)**

Tools we may use:
- **XFoil**
- **CFD Python**
- **OpenFOAM**

---

## 🔧 Tools / Technologies
| Tool | Purpose |
|------|---------|
| Python | Core programming |
| PyTorch / TensorFlow | Diffusion model |
| NumPy / Pandas | Data handling |
| Matplotlib | Visualization |
| XFoil / OpenFOAM | Aerodynamic simulation |

---

## 👥 Team Members
- **Shola**
- **Abibat**
- **Mohammed**


---

## 🚀 How to Run the Project (Instructions will be added later)
```bash
python train_diffusion.py
python generate_airfoils.py

