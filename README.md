# FFO-EESA: Power-Aware VM Placement
## IEEE Conference Paper by Subrahmanyam Tanala

**8.2% energy savings** • **100 hosts/800 VMs** • **Google cluster traces**

| Method | Energy | Hosts | Savings |
|--------|--------|-------|---------|
| **FFO-EESA** | **11,520 kW** | **34/100** | **8.2%** |
| First-Fit | 12,540 kW | 41/100 | - |

### 🚀 Reproduce Results
```bash
pip install numpy pandas scikit-optimize matplotlib
python firefly_vm.py  # Generates 8.2% results
pdflatex main.tex     # IEEE paper PDF
