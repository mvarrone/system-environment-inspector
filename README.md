# 🧠 System & Environment Inspector 🚀

## Overview

The System & Environment Inspector is a comprehensive Python-based tool designed to gather detailed information about your system environment. This tool is particularly useful for AI workflows, ensuring that your hardware and software environment is properly configured for machine learning tasks.

## Features

The inspector provides detailed information on:

- 💻 **Hardware Specifications**: 
  - CPU details (cores, frequency, usage)
  - RAM information (total, available, used)
  - GPU specifications (if available)

- ⚙️ **Software Environment**: 
  - Operating System details
  - Python version
  - Installed package versions (PyTorch, TensorFlow)

- 🔍 **CUDA Availability**: 
  - CUDA version
  - TensorFlow GPU availability

- 🌐 **Network Information**: 
  - Hostname
  - Local IP address

## Requirements

- Python 3.9+
- Required Python packages:
  - psutil
  - py-cpuinfo
  - torch
  - tensorflow

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/mvarrone/system-environment-inspector.git
   cd system-environment-inspector
   ```

## Usage

1. Open the `system_overview.ipynb` notebook in Jupyter Lab or Jupyter Notebook.
2. Run all cells in the notebook to get a comprehensive report of your system.

## Output

The tool provides a detailed report with sections for:

- System Information
- RAM Information
- CPU Information
- GPU Information
- TensorFlow GPU Information
- OS-Specific Information
- Installed Package Versions
- Network Information

## Contributing

Contributions to improve the System & Environment Inspector are welcome. Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- This tool uses various Python libraries including `psutil`, `py-cpuinfo`, `torch`, and `tensorflow`.
- Special thanks to the open-source community for their invaluable contributions to the libraries used in this project.