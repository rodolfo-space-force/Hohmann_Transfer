# Hohmann Transfer

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/topics/python)

# Graphical Orbital Visualization of a Hohmann Transfer

This repository contains a Python script for the analytical computation and graphical visualization of a **Hohmann transfer maneuver**, used to transfer a spacecraft between two circular Earth orbits with minimum propellant expenditure.

---

## Description

The Hohmann transfer is a two-impulse orbital maneuver widely applied in space missions to achieve orbit changes with optimal energy efficiency.

This project:

- Accepts user-defined initial (`r1`) and final (`r2`) orbital radii;
- Computes the semi-major axis of the transfer ellipse;
- Calculates required velocity increments (Δv₁ and Δv₂);
- Generates a graphical visualization including:
  - Earth at the center;
  - Initial circular orbit;
  - Final circular orbit;
  - Transfer ellipse;
  - Impulse vectors (Δv₁ and Δv₂);
  - Highlighted perigee and apogee.

---

## Applications

This script is suitable for:

- Orbital mechanics demonstrations;
- Aerospace engineering coursework;
- Preliminary trajectory design analysis;
- Educational visualization of two-impulse transfer strategies.

---

## Example Usage

Input the requested values:

```text
Enter the initial orbital radius (r1) in km (e.g., 6578):
Enter the final orbital radius (r2) in km (e.g., 42250):

![Texto alternativo da imagem](orbita.png)

You can reach me at rmilhomem[at]gmail[dot]com or connect on [LinkedIn](https://www.linkedin.com/in/rodolfo-space-force/) for collaborations.

## Licença

Este projeto está licenciado sob a Licença MIT. Você pode usar, modificar e redistribuir este código livremente, desde que mencione o autor original.

[![MIT License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)

