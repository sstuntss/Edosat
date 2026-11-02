# Edosat

Open satellite dataset for Edo State, Nigeria. Built off-grid from Benin City.

## v0.1 - 18 LGAs
- **Data:** Sentinel-2 L2A (10m resolution)
- **Processing:** NDVI (Normalized Difference Vegetation Index) to highlight vegetation health and urban areas.
- **Coverage:** All 18 LGAs in Edo State.
- **Format:** PNG images (Grey = Urban/Bare, Yellow = Sparse, Green = Healthy Vegetation)

## Why?
No open, LGA-indexed satellite dataset exists for Nigeria. Researchers and NGOs currently have to build this from scratch. Edosat makes it available for AI models, deforestation tracking, and agricultural monitoring.

## Roadmap
- [x] v0.1: Edo State (18 LGAs)
- [ ] v1.0: All 774 Nigerian LGAs
- [ ] v2.0: AI Deforestation Detection Model

## Built by
Kamoru Destiny, Benin City.
## AI Model Preview
![K-Means Clustering](kmeans_ai_preview.png)
*Unsupervised K-Means clustering applied to the Oredo LGA satellite imagery.*
## State-wide AI Maps (v0.2 Preview)
The Random Forest classifier has been run across all 18 LGAs in Edo State. 

*Preview:* 4 AI-classified maps (including Oredo and Esan Central) are uploaded in this repository. The complete dataset of all 18 AI maps can be generated using the provided Python scripts.
