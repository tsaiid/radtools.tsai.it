# RadTools - Clinical Radiology Utilities

This repository, `radtools.tsai.it`, is a collection of web-based utilities designed to assist in clinical radiology workflows. Developed by Dr. Tsai, these tools aim to improve the accuracy and efficiency of medical decision-making.

The project serves as a central hub for various applications, accessible via a main landing page.

## Deployed Tools

The following tools are available:

### 1. Bone Age Atlas
- **Link:** [/bone-age/](https://radtools.tsai.it/bone-age/)
- **Description:** An implementation of the Greulich & Pyle bone age reference atlas. It serves as a visual aid for assessing skeletal maturity in pediatric imaging.

### 2. AJCC Cancer Staging
- **Link:** [/structure-report/ajcc/](https://radtools.tsai.it/structure-report/ajcc/)
- **Description:** A report generator for creating structured cancer staging reports based on the latest American Joint Committee on Cancer (AJCC) guidelines. It helps in producing standardized medical records efficiently. The repository contains templates for AJCC 7th, 8th, and 9th editions.

### 3. Lung-RADS Report
- **Link:** [/structure-report/nhi-lung-rads/](https://radtools.tsai.it/structure-report/nhi-lung-rads/)
- **Description:** A specialized reporting tool for lung cancer screening using Low-Dose Computed Tomography (LDCT), aligned with the Taiwan National Health Insurance (NHI) program. It features automatic risk classification based on the Lung-RADS assessment category.

### 4. Duty Roster
- **Link:** [/random-duty/](https://radtools.tsai.it/random-duty/)
- **Description:** A smart scheduling tool designed to generate duty rosters. It facilitates the fair and balanced allocation of human resources within a medical department.

## Repository Structure

The repository is organized into directories, with each directory representing a separate tool:

- `bone-age/`: Contains the Bone Age Atlas tool.
- `random-duty/`: The Duty Roster generator.
- `structure-report/`: A collection of structured reporting tools, including:
    - `ajcc/`, `ajcc8/`, `ajcc9/`: Different versions of the AJCC staging tool.
    - `nhi-lung-rads/`: The Lung-RADS reporting tool.
- `vghks-calendar/` & `vghks-random-duty/`: Additional tools, likely specific to a department or institution (VGHKS).
- `index.html`: The main landing page that links to all the tools.
