
<div align="center">

# Internship Report: Fixaars Application

### Realization of an application for connecting local service providers

![Cover Page](assets/demo/cover.jpg)

</div>

<p align="center">
  <a href="https://github.com/yaasiin-ayeva/fixaars-internship-report/blob/main/main.pdf" target="_blank" rel="noreferrer noopener">
    <img src="https://img.shields.io/badge/View%20Report-PDF-red?style=for-the-badge&logo=adobe-acrobat-reader" alt="View PDF">
  </a>
  <img src="https://img.shields.io/badge/Language-French-blue?style=for-the-badge" alt="Language">
  <img src="https://img.shields.io/badge/Technology-Node.js%20%26%20TypeScript-green?style=for-the-badge&logo=nodedotjs" alt="Technology">
</p>

This repository contains the complete LaTeX source code for my final year internship report. The report details the analysis, design, and implementation of **Fixaars**, a web platform for connecting users with local service providers.

-   **Author:** Yaasiin AYEVA
-   **Institution:** IFNTI (Institut de Formation aux Normes et Technologies de l'Informatique)
-   **Host Company:** JS Morlu Ghana
-   **Internship Period:** 29/01/2024 to 28/06/2024

---

## Table of Contents

-   [Project Abstract](#project-abstract)
-   [Technology Stack](#technology-stack)
-   [How to View the Report](#how-to-view-the-report)
-   [How to Compile the Source](#how-to-compile-the-source)
-   [Repository Structure](#repository-structure)
-   [Acknowledgements](#acknowledgements)
-   [License](#license)

## Project Abstract

The **Fixaars** project was initiated to address the fragmented and often inaccessible market for local professional services in Ghana. The goal was to create an innovative digital platform to centralize and simplify access to a wide range of services (plumbing, electricity, gardening, etc.).

The application connects service seekers with qualified providers, offering features such as:
-   Targeted service provider search with advanced filters.
-   Detailed professional profiles with skills, availability, and user reviews.
-   An integrated real-time chat module with audio/video call capabilities.
-   A transparent rating and review system to build a trusted community.

This project was developed following an **Agile methodology** and a **backend-first** approach, ensuring a robust, scalable, and maintainable architecture.

## Technology Stack

The solution was built using a modern and powerful technology stack to ensure performance, flexibility, and maintainability.

| Category                | Technologies & Tools                                                                      |
| ----------------------- | ----------------------------------------------------------------------------------------- |
| **Backend**             | Node.js, TypeScript, Express.js                                                           |
| **Database & ORM**      | PostgreSQL, TypeORM                                                                       |
| **Frontend & Templating** | EJS (Embedded JavaScript), Bootstrap, HTML5/CSS3                                          |
| **Real-Time Communication** | Socket.IO, PeerJS (for WebRTC)                                                            |
| **Development & DevOps**  | Git, Bitbucket, Postman, Jira, CI/CD Pipeline (on Hostinger VPS)                           |
| **Authentication**      | JWT, Social Authentication (Google, Facebook, LinkedIn)                                   |

## How to View the Report

The easiest way to read the report is to view the pre-compiled PDF file included in this repository.

<p align="center">
  <a href="https://github.com/yaasiin-ayeva/fixaars-internship-report/blob/main/main.pdf" target="_blank" rel="noreferrer noopener">
    <strong>➡️ View the Final Report (PDF) ⬅️</strong>
  </a>
</p>

## How to Compile the Source

If you wish to compile the report from the LaTeX source code, follow these steps:

1.  **Prerequisites**:
    -   A complete LaTeX distribution such as **TeX Live**, **MiKTeX**, or **MacTeX**.
    -   The `latexmk` utility is recommended for a simple, one-command compilation.

2.  **Clone the repository**:
    ```bash
    git clone https://github.com/yaasiin-ayeva/fixaars-internship-report.git
    cd fixaars-internship-report
    ```

3.  **Compile the document**:
    Run the following command in the root directory. `latexmk` will automatically handle multiple passes, bibliography, and table of contents generation.
    ```bash
    latexmk -pdf main.tex
    ```
    This will generate the `rapport.pdf` file in the root directory. You may need to run it a second time for the table of contents to be fully updated.

## Repository Structure

The repository is organized to separate the LaTeX content from the visual assets, ensuring the project remains clean and manageable.

```
.
├── main.tex              # The main LaTeX file that includes all other parts.
├── rapport.pdf           # The final, compiled PDF report.
├── bibliographie.bib     # The bibliography file in BibTeX format.
├── LICENSE
├── README.md
│
├── title.tex             # LaTeX source for the title page.
├── epigraph.tex          # LaTeX source for the epigraph.
├── abstract.tex          # LaTeX source for the abstract/remerciements.
├── introduction.tex      # Chapter: Introduction.
├── presentation.tex      # Chapter: Presentation of the company and project.
├── demo.tex              # Chapter: Technical implementation and demonstration.
├── annexes.tex           # Main file for including all annexes.
├── annexe1.tex           # Annex 1: Backend implementation details.
└── annexe2.tex           # Annex 2: Frontend implementation details.
│
└── assets/               # Directory containing all visual media.
    ├── annexes/          # Screenshots of code snippets for the technical annexes.
    ├── demo/             # UI screenshots demonstrating the application's features.
    ├── diagrams/         # UML diagrams (Use Case, Class diagrams) for analysis.
    └── presentation/     # Logos, architectural diagrams, and other assets.
```

## Acknowledgements

I would like to extend my deepest gratitude to my supervisor, **[M. Aliloulaye TCHAOU](https://www.jsmorlu.com/about-js-morlu-llc/our-team/aliloulaye-tchaou/)**, for his guidance and trust throughout this internship. My sincere thanks also go to my family, the staff at **IFNTI-Sokodé**, and the entire team at **JS Morlu Ghana** for their invaluable support, warm welcome, and the enriching learning experience.

This README's structure was inspired by the [WebLaTex](https://github.com/sanjib-sen/WebLaTex) project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.