# Programming II (Java)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/uETITC/ProgrammingII-2024-2/main?labpath=Lessons)

## Tabla de Contenido (ToC)

```{tableofcontents}
```

## Executing Notebooks in Colab


::::{important}
If you work from [Google Colab](https://colab.research.google.com/) **you must** execute the following code block in every notebook, at beginning. Remember that the tutorial on how to configure the environment can be found in the first tutorial: [1. Intruduction To Java](https://github.com/uETITC/ProgrammingII-2024-2/blob/main/Lessons/1.%20IntroductionToJava.md#instalando-el-kernel-de-java). There are several ways and Google Colab is one of them.

  :::{code} python
  :class: dropdown
  %%sh
  %%capture
  # Install java kernel
  wget -q https://github.com/SpencerPark/IJava/releases/download/v1.3.0/ijava-1.3.0.zip
  unzip -q ijava-1.3.0.zip
  python install.py

  # Install proxy for the java kernel
  wget -qO- https://gist.github.com/SpencerPark/e2732061ad19c1afa4a33a58cb8f18a9/archive/b6cff2bf09b6832344e576ea1e4731f0fb3df10c.tar.gz | tar xvz --strip-components=1
  python install_ipc_proxy_kernel.py --kernel=java --implementation=ipc_proxy_kernel.py
  :::
  
::::

## Objective

{cite}`ydaniel,koffman,jamest`.

To train students in problem solving through object-oriented programming (OOP). Throughout the course, students will learn to apply advanced modular programming techniques, to reuse code through libraries and frameworks, and to develop complex solutions through debugging and logical reasoning processes.

In addition, the course aims for students to acquire additional competencies in key areas such as developing applications with graphical user interfaces using JavaFX, implementing recognized design patterns such as Factory and MVC, and managing persistence and database connection in their applications. These skills will enable students to create robust and efficient software, aligned with the needs of the work environment.

## Subject Learning Results (RAC)

At the end of the course the student will be able to:

**RAC1**. Solve problems by applying object-oriented programming.

**RAC2**. Apply modular programming techniques and code reuse, using libraries and frameworks.

**RAC3**. Develop step-by-step solutions applying debugging techniques and logical reasoning to solve complex programming problems.

## Grades

::::{grid}
:gutter: 2

:::{grid-item}
```{list-table} Exams dates.
:header-rows: 1
:name: exams

* - **Period**
  - **Date**
* - First
  - 12/09/2024
* - Second
  - 24/10/2024
* - Final
  - 28/11/2024
```
:::
:::{grid-item}
:margin: auto auto 0 0 
```{list-table} Project deliveries dates.
:header-rows: 1
:name: proeject

* - **Presentation**
  - **Date**
  - **Porcentage**
* - First
  - 16/09/2024
  - 10 %
* - Second
  - 17/11/2024
  - 10 %
* - Final
  - 02/12/2024
  - 80 %
```
:::
::::


For all periods the grade is divided into: Co-evaluation (10 %), self-evaluation (10 %), and teacher evaluation (80 %) which is divided into exams (30 %) and assignments (50 %). The first and second periods are 35 % of the final grade, while for the last period it is 30 %. In the first and second periods the exam consists of two tests: one practical (60 %) and the other theoretical (40 %). 

The project is divide in two grades: first report (20 %) and last (80 %) assignment.

:::{tip}
You can practice and complement the course by solving programming problems in any of the following pages:

- [Codeabbey](https://www.codeabbey.com/)
- [Hackerrank](https://www.hackerrank.com/)
- [LeetCode](https://leetcode.com/)

Each solved problem, which has passed all the tests created for the page, can be exchanged for points. Very simple problems are not valid.
:::

## Assigments

All assignments will be stored on [GitHub](https://github.com/) but will be uploaded for grading on [Campus Virtual](https://campusvirtualpes.etitc.edu.co/Edusuperior/). 

## Projects

::::{grid}
:gutter: 2

:::{grid-item-card} [Analysis and visualization of audios on Java](https://github.com/mrcastillor/Cantos_de_aves)
- Jose Mateus
- Miguel Lara
- Manuel Castillo
- Lenin Cruz
:::

:::{grid-item-card}  [ETITC Parking (bykes, cars, and motorbikes)](https://github.com/Estebaniza/PROYECTO-PROGRAMACION-2)
- Cristian Camilo Espinosa
- Diego Fernando Báez
- Juan Esteban Joven
- Michael Pinzón
:::
::::

::::{grid}
:gutter: 2

:::{grid-item-card} [Intelligent chatbot/agent](https://github.com/AndresMolin4/ChatBot)
- Carlos Sotelo 
- Andres Molina
- Edison Rincon
- Juan David Bejarano 
:::

:::{grid-item-card} [ETITC Restaurant](https://github.com/Edwin-Bautista-Gil/ETITC.Restaurant/)
- Johan Alexis Hernandez Sanchez
- Edwin Leonardo Bautista Gil
- Sara Milena Villacorte Pedraza
- Brayan Stiven Sandoval Reyes
:::
::::

::::{grid}
:gutter: 2

:::{grid-item-card} [ETITC workers attendence](https://github.com/Lorena0127/AsistenciaDeTrabajadores)
- Danna Sofía Rojas Flórez 
- Diana Lorena Salinas Ortegón
- Juan Diego 
:::

:::{grid-item-card} 
:::
::::

## References

### Guides and Tutorials

- [Guía oficial de Oracle sobre Programación Orientada a Objetos en Java](https://docs.oracle.com/javase/tutorial/java/concepts/index.html)
- [Tutorial sobre POO en Java de GeeksforGeeks](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)

### Repositories

- [Java Tutorial for Beginners ](https://www.youtube.com/watch?v=eIrMbAQSU34)
- [Learn Java in One Video - 15-minute Crash Course ](https://www.youtube.com/watch?v=drQK8ciCAjY)
- [Java Roadmap for 2024 ](https://www.youtube.com/watch?v=fO9HN3nvDLI)
- [Java Tutorial for Beginners 2023 ](https://www.youtube.com/watch?v=BGTx91t8q50)
- [Intro-to-Java-Programming](https://github.com/jsquared21/Intro-to-Java-Programming)
- [Source Code - Introduction to Java Programming and Data Structures, Comprehensive Version, 12th Edition](https://media.pearsoncmg.com/ph/esm/ecs_liang_ijp_12/cw/content/source-code.php)

### Books

```{bibliography}
```

:::{important}
You can find all reference in the Google Drive folder [References](https://itceduco-my.sharepoint.com/:f:/g/personal/saguileran_itc_edu_co/Eledh23Sd41CnWAnmM3jALkBNHxwDXfiZ4CcmnRTa_ST3Q?e=Z1qPlS).
:::