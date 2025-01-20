# Voronoi Generator
> An interactive tool for generating **custom Voronoi diagrams** with real-time adjustments.
<table style="border-collapse: collapse; border: none;">
  <tr>
    <td><img src="figures/example1.png" width="100%"></td>
    <td><img src="figures/example2.png" width="100%"></td>
  </tr>
  <tr>
    <td><img src="figures/example3.png" width="100%"></td>
    <td><img src="figures/example4.png" width="100%"></td>
  </tr>
</table>

<br>

## Features
- Custom **colors, textures, and density settings**.
- Save & load configurations (`.json`).
- Export Voronoi diagrams as **high-resolution PNG images**.
- Interactive user interface with **real-time updates**.
- Logging system for monitoring rendering times and settings.

## Installation

### Requirements
- Python 3.8+  
- Jupyter Notebook (`pip install jupyterlab` if not installed)

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. Open **`voronoi.ipynb`** in Jupyter Notebook (`jupyter notebook` in a terminal).
2. Adjust parameters using **interactive sliders and dropdown menus**.
3. Generate and preview the **Voronoi diagram**.
4. Save configurations for future use.
5. Export generated images in `.png` format.

## Example Outputs
| ![Voronoi](figures/Gregory-Voronoy_high-detail.png) | ![Tiger](figures/tiger_stylized.png) |
|:--------------------------------------------------:|:------------------------------------:|
| *Georgy Voronoy* | *High-Detail Tiger* |


<br>

## Benchmark

Performance tests were conducted using different configurations to assess execution speed.  
Unsurprisingly, the number of Voronoi points is directly related to execution time. However, rounding the edges also significantly slows down execution.


<br>

---

## Contact
📩 **Email**: [mathieu.sterlin@gmail.com](mailto:mathieu.sterlin@gmail.com)  
🐙 **GitHub**: [mathieu-portfolio](https://github.com/mathieu-portfolio/)

