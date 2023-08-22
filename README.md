# Hospital Facility Accessibility Analysis in Olongapo City, Zambales

This repository contains the materials and documentation used for the case study. Geospatial tools and techniques were utilized to analyze hospital facility accessibility in Olongapo City, Zambales. QGIS was used primarily for the analysis while Python was used to perform automated geotagging through the Google Geotagging API.

## Table of Contents

- [Objective](#objective)
- [Methodology](#methodology)
- [Materials](#materials)
- [Data](#data)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Objective

The general objective of this case study is to conduct a comprehensive analysis of hospital facility accessibility in Olongapo City, Zambales. Specifically, the case study aims to:

1. Identify and map the current distribution of hospital facilities within Olongapo City, Zambales, to understand the spatial availability of healthcare services.
2. Develop an origin-destination matrix that will serve as the basis for analyzing hospital accessibility
3. Propose potential locations for new hospital facilities or expansion of existing ones to address accessibility gaps

## Methodology

The following processes were performed to conduct the case study:

1. **Data Collection:** Relevant data on hospital locations using the Department of Health - National Health Facility Registry (DOH - NHFR), road networks from OpenStreetMap, and population distribution were collected. 

2. **Data Preparation:** The collected data is cleaned, processed, and transformed into suitable formats for analysis. Geospatial data such as hospital coordinates and road networks were prepared by the author for use in QGIS.

3. **Spatial Analysis:** QGIS is utilized to conduct spatial analysis. Hospital locations were mapped, and distance-based calculations were performed using QNEAT3 OD Matrix Calculation. 

4. **Geotagging Automation:** Python script was used to automate geotagging since this case study is envisioned to be implemented at a larger scale in the future – automated geotagging would make the process of collecting longitude and latitude pairs of hospitals locations more efficient. 

5. **Analysis and Recommendations:** The results were interpreted to understand hospital accessibility patterns and identify areas with limited access to healthcare facilities. Based on the analysis, recommendations for new hospital locations or expansion of existing ones are proposed to improve accessibility.

## Materials

The following tools are employed in this case study:

- **QGIS:** A powerful open-source geographic information system used for spatial analysis, mapping, and visualization.

- **Visual Studio Code:** An integrated development environment (IDE) for Python programming, providing tools for efficient code development.

## Data

The case study utilizes the following data sources:

- Olongapo City Hospitals from the Department of Health - National Health Facility Registry (DOH - NHFR)
- Philippines Administrative Boundary Shapefiles
- OpenStreetMap Road Network Data
- Population Distribution Data

## Results

_Results and discussion will be posted once the case study is done._

## Usage

To replicate or build upon this study:

1. Clone this repository to your local machine.
2. Ensure you have QGIS and Visual Studio Code with Python installed.
3. Use the provided data or replace it with your own relevant datasets.
4. Follow the scripts and documentation to execute the analysis steps outlined in the methodology.

## Contributing

Contributions to this repository are welcome. If you find issues or want to enhance the analysis, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

__Kahlil Sebastian Ramos__
_Science Research Specialist I_
Department of Science and Technology - Advanced Science and Technology Institute (DOST-ASTI)
22 August 2023

Feel free to customize the content, including [Your Name] and [date], and ensure that the license, methodology, and instructions are accurate for your case study.
