<!-- PROJECT SHIELDS -->
[![Colaboradores][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Estrellas][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Formatos de Tareas PUCE</h3>
  <p align="center">
    Formato de LaTeX para la elaboración de tareas de estudiantes de la PUCE.  
    <br />
    <a href="https://github.com/andres-merino/Formato-Tareas-PUCE/issues">Reportar un Problema</a>
    ·
    <a href="https://github.com/andres-merino/Formato-Tareas-PUCE/issues">Solicitar cambio</a>
    <br />
    Abrir en 
    <br />
    <a href="https://www.overleaf.com/read/vhdczzsymytd#3bf1e4">
    <img src="https://img.shields.io/badge/Overleaf-47A141?logo=overleaf&logoColor=fff&style=for-the-badge" alt="Overleaf Badge">
    </a>
  </p>
</div>



## About the Project

This project provides a LaTeX template for preparing student assignments at the Pontificia Universidad Católica del Ecuador. The template adheres to the university's visual identity and bibliography guidelines. It includes environments for creating exercises, problems, solutions, and code, among other elements.

### Built with

[![LaTeX][LaTeX]][LaTeX-url]


## Description


Two examples are provided: the first is an example of an essay-style assignment demonstrating how to include images, tables, and code, as well as how to cite sources and include a bibliography. The second example is the solution to a mathematics problem, including both the problem statement and the solution.



The packages used for the title format are [`titling`](https://ctan.org/pkg/titling) y [`authblk`](https://ctan.org/pkg/authblk). 

The Montserrat font is used via the package [`montserrat`](https://ctan.org/pkg/montserrat) (in the case of compilation with LaTeX or pdfLaTex) and [`fontspec`](https://ctan.org/pkg/fontspec) (in the case of compilation with XeLaTeX).

The `watermark.pdf` file, which contains the university's visual identity, is used as the background for each page.

For the bibliography, the [`biblatex`](https://ctan.org/pkg/biblatex) package is used with the `apa` style.


The `math-block` environment is defined for writing exercise statements. To define additional environments, the following code can be included:


```latex
\newtheorem{math-block}{Exercise}
    \tcolorboxenvironment{ejer}{%
        color=colordef,recuadrost,colback=colordef!7,drop fuzzy shadow
    }
```


## Credits 


Forked from:  https://github.com/andres-merino/Formato-Tareas-PUCE

Andrés Merino\
[Proyecto Alephsub0](https://www.alephsub0.org/about/),\
Docente Investigador\
Pontificia Universidad Católica del Ecuador\
aemerinot@gmail.com\
[![LinkedIn][linkedin-shield]][linkedin-url-aemt]


## Licencia

Distribuido bajo la licencia MIT. 

[![MIT License][license-shield]][license-url]




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[contributors-url]: https://github.com/andres-merino/Formato-Tareas-PUCE/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[forks-url]: https://github.com/andres-merino/Formato-Tareas-PUCE/forks
[stars-shield]: https://img.shields.io/github/stars/andres-merino/Formato-Tareas-PUCE?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[issues-url]: https://github.com/andres-merino/Formato-Tareas-PUCE/issues
[license-shield]: https://img.shields.io/github/license/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[license-url]: https://es.wikipedia.org/wiki/Licencia_MIT
[linkedin-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-aemt]: https://www.linkedin.com/in/andrés-merino-010a9b12b/
[LaTeX]: https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=fff&style=for-the-badge
[LaTeX-url]: https://www.latex-project.org/
