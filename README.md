# Integration of Simatic Manager (S7-300 PLC) and HMI (WinCC)

This project demonstrates the integration of **Siemens Simatic Manager (STEP 7, S7-300 PLC)** with **WinCC HMI** for basic arithmetic operations.  
The PLC program performs **SUM, SUB, MUL, DIV** operations, and the results are displayed on an HMI screen.

---

## 🚀 Project Overview
- **PLC Platform**: Siemens Simatic Manager (STEP 7, S7-300)  
- **HMI Platform**: Siemens WinCC (Advanced)  
- **Programming Language**: Ladder Logic (LAD)  
- **Operations Implemented**:  
  - Addition (SUM)  
  - Subtraction (SUB)  
  - Multiplication (MUL)  
  - Division (DIV)  

The goal of this project is to practice **PLC programming** and **HMI integration** for real-time monitoring and control of arithmetic operations.

---

## 📂 Project Structure
    📁 Integration-Simatic-HMI
    │── 📁 PLC_Code # Ladder logic program for S7-300
    │── 📁 HMI_Screens # WinCC project files
    │── 📄 README.md # Project documentation
---

## 🔧 Features
- Input values can be entered from **HMI (WinCC)**.  
- Results of operations are displayed on **HMI in real-time**.  
- User-friendly interface for selecting the desired operation.  

---

## 🛠️ Requirements
- **Software**:  
  - Siemens STEP 7 (Simatic Manager)  
  - Siemens WinCC (Flexible/Advanced)  

- **Hardware (Optional for Simulation)**:  
  - Siemens S7-300 PLC  
  - Siemens HMI Panel (KTP series)  

- **Simulation**:  
  - Can be tested with **PLCSIM + WinCC Runtime**  

---

## ⚙️ Implementation Details

### PLC Program
**Inputs:**  
- Operand 1 (INT)  
- Operand 2 (INT)  
- Operation Selector (SUM, SUB, MUL, DIV)  

**Outputs:**  
- Operation Result  

### HMI (WinCC)
- Numeric input fields for Operand 1 and Operand 2.  
- Buttons to select the operation.  
- Display field for showing the result.  

---

## ▶️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/nrasel/Simatic-Manager-HMI-WinCC-integration.git
   cd Simatic-Manager-HMI-WinCC-integration
