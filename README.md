# Design and Analysis of a Hypersonic Glide Vehicle (HGV)

## Overview  
This project focuses on the conceptual design and aerodynamic analysis of a **Hypersonic Glide Vehicle (HGV)** capable of sustained flight at speeds above Mach 5. The study emphasizes understanding aerodynamic efficiency, lift-to-drag optimization, and material selection to ensure vehicle stability and performance at hypersonic speeds. The work combines theoretical calculations and computational analysis to evaluate the feasibility of a blended HGV design.

---

## Objectives  
- To design a conceptual **hypersonic glide vehicle** optimized for high lift-to-drag ratio.  
- To analyze aerodynamic parameters such as lift, drag, and pressure distribution at hypersonic conditions.  
- To study the **effects of nose geometry and wing sweep** on aerodynamic performance.  
- To compare different configurations and identify the most aerodynamically efficient design.  

---

## Methodology  

### 1. Conceptual Design  
- The HGV was modeled using **CATIA V5** with a **blended body-wing configuration** for reduced wave drag.  
- The design included three different nose shapes: **sharp conical**, **blunt**, and **ogive**, each tested for aerodynamic efficiency.  
- The overall geometry aimed to maintain a smooth surface profile to minimize drag and improve thermal resistance.

### 2. Computational Setup  
- The aerodynamic simulations were performed using **ANSYS Fluent** under **Mach 5** flow conditions.  
- A **structured hexahedral mesh** was generated around the HGV model to capture boundary layer effects accurately.  
- The flow domain used **air as a compressible fluid**, with conditions:
  - Mach Number: 5  
  - Altitude: 30 km  
  - Temperature: 226.5 K  
  - Pressure: 1.19 kPa  

### 3. Analysis Procedure  
- Governing equations of **compressible viscous flow** were solved using **k–ω SST turbulence model**.  
- Simulations were performed for each nose configuration.  
- Lift and drag coefficients were extracted and compared to identify aerodynamic advantages.  

---

## Results and Discussion  

| Nose Type | Lift Coefficient (Cl) | Drag Coefficient (Cd) | L/D Ratio | Observation |
|------------|-----------------------|-----------------------|------------|--------------|
| Sharp Conical | 0.056 | 0.021 | 2.66 | Least drag, but structurally vulnerable |
| Blunt | 0.071 | 0.035 | 2.02 | Stable flow but higher drag |
| Ogive | 0.064 | 0.024 | 2.67 | Best compromise between lift and drag |

- The **ogive nose design** provided the most balanced performance with good aerodynamic efficiency and structural reliability.  
- Flow visualization showed reduced separation and smoother shock formation around the ogive configuration.  
- Temperature contours indicated that the **sharp nose experienced the highest stagnation heating**, confirming the trade-off between drag and thermal protection.  

---

## Conclusion  
The study demonstrated that **nose geometry plays a crucial role** in determining the aerodynamic efficiency and thermal loading of hypersonic glide vehicles. Among the tested configurations, the **ogive nose design** achieved the best lift-to-drag ratio while maintaining manageable heating effects, making it the most viable option for sustained hypersonic flight.  
The results validate the importance of shape optimization in HGV design, where both **aerodynamic and thermal factors** must be balanced for optimal performance.

---

## Future Work  
- Conduct **CFD analysis at different Mach numbers (5–10)** to understand speed dependency.  
- Include **thermal protection system (TPS) modeling** for realistic performance evaluation.  
- Integrate **trajectory and stability analysis** for complete flight profile assessment.  
- Explore **adaptive geometries** and **aerospike integration** for drag reduction.

---

## Tools and Technologies  
- **Design:** CATIA V5  
- **Simulation:** ANSYS Fluent  
- **Turbulence Model:** k–ω SST  
- **Flow Type:** Compressible, Hypersonic (Mach 5)  

---

## Authors  
- Krisha Kotian Manish  
- [Team Members, if applicable]  
- Guide: [Faculty Guide Name, if applicable]  
- Department of Aerospace Engineering, SRM Institute of Science and Technology, Chennai  

---

## Citation  
> Kotian, K., *Design and Analysis of a Hypersonic Glide Vehicle (HGV)*, SRM Institute of Science and Technology, 2025.  
