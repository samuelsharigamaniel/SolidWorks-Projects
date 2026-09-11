Biomimetic Tongue Surface CAD Model

Description: This repository contains CAD drawings of a biomimetic tongue surface designed to replicate the topographical characteristics of the human tongue. The model is based on the morphology and spatial distribution of lingual papillae reported in previous biomimetic tongue research by Andablo-Reyes, Neville, Sarkar and co-authors (3D biomimetic tongue-emulating surfaces for tribological applications. ACS applied materials & interfaces (2020))

The tongue surface was designed to reproduce the heterogeneous texture created by two primary papillae types:

Filiform papillae: densely distributed structures responsible for the majority of tongue surface roughness.
Fungiform papillae: larger, sparsely distributed dome-like structures interspersed among the filiform papillae.

The spatial arrangement of the papillae was generated using a randomized distribution approach based on a Poisson Point Process (PPP). Random Cartesian coordinates were generated within a 30 mm × 30 mm surface area. Any overlapping papillae locations were removed and regenerated until all features satisfied the minimum spacing requirements. Fungiform papillae were generated first due to their larger dimensions, followed by filiform papillae.

To improve manufacturability, filiform papillae were modeled as frustums of cones rather than perfect cylinders. This geometry provides a draft angle that facilitates mold release and reduces the risk of damage during demolding. Fungiform papillae were represented as dome-shaped features.


Surface Parameters

Filiform Papillae
- Height: 150 µm
- Diameter: 300 µm
- Density: 170 papillae/cm²
- Geometry: Frustum of a cone

Fungiform Papillae
- Height: 400 µm
- Diameter: 800 µm
- Density: 14 papillae/cm²
- Geometry: Dome-shaped

Design Assumptions
- Surface area: 30 mm × 30 mm
- Randomized papillae distribution using a Poisson Point Process
- Non-overlapping feature placement
- Dimensions and densities selected to represent average human tongue surface morphology reported in literature

Purpose: The model was developed for the fabrication of biomimetic tongue surfaces for tribological, texture, oral processing, and food-material interaction studies where realistic replication of tongue surface roughness and papillae distribution is required.
