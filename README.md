# ICE-HUNTER
A zero-backend client-side web application for NASA's SPHEREx mission featuring real-time sky time-lapse generation, difference imaging, 102-band live spectra, and an Ice Lab volatile simulator.
# 🔭 Ice Hunter: PLANET X & SPHEREx Explorer

**Developed for NASA's SPHEREx Mission by TEAM STRIVE GBI**  
*Team Members:* Sushweta Ghosh, Sanhita Bhattacharjee, Indrani Deb Roy  

---

## 🚀 1-Liner Pitch
> *"Explore NASA’s SPHEREx sky data in real time, build interactive time-lapse videos to track moving objects, and analyze cosmic ices instantly with Ice Hunter."*

---

## ✨ Key Features

* **Sky Time-Lapse & Difference Engine:** Instantly query multi-epoch cutout sequences via NASA IRSA TAP/cutout APIs, perform difference imaging, and overlay Gaia DR3 and AllWISE astrometry to spot moving objects and transients.
* **On-the-Fly 102-Band Spectra:** Extract aperture and PSF photometry across all 102 SPHEREx near-infrared channels directly in the browser.
* **Ice Lab Simulator:** Analyze molecular ice absorption features ($\text{H}_2\text{O}$, $\text{CO}_2$, $\text{CO}$), compute optical depths, and estimate column densities.
* **Zero Backend Architecture:** Runs 100% client-side in standard web browsers with direct API access to NASA IRSA and VizieR, deployable on static hosting (GitHub Pages, Netlify).

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (Single-file `index.html` deployment)
* **Data Visualization & Processing:** HTML5 Canvas, WCS Coordinate Transformations, custom spectral plotting engines
* **APIs & Data Access:** NASA/IPAC IRSA TAP & Cutout Services, CDS VizieR (Gaia DR3 & AllWISE)
* **Hosting:** Static Web Hosting (Zero server-side dependencies)

---

## 🔗 Official NASA Data & References

* [NASA/IPAC Infrared Science Archive (IRSA) TAP](https://irsa.ipac.caltech.edu/TAP)
* [NASA SPHEREx Mission Overview](https://www.jpl.nasa.gov/missions/spherex)
* [NASA SPHEREx Data & Tools](https://spherex.caltech.edu/data-tools)
* [CDS VizieR Service](http://tapvizier.cds.unistra.fr)

---

## 📄 License
This project is open-source and built for NASA space challenge applications.
