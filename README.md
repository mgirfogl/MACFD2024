 [![Creative Commons License](http://mirrors.creativecommons.org/presskit/logos/cc.logo.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)


# Models and Applications in Computational Fluid Dynamics

- Michele Girfoglio (<mgirfogl@sissa.it>)

## Program

The course refers to the use of computational fluid dynamics techniques to address advanced applications in environmental, cardiovascular and industrial contexts. Each topic will be corroborated by a set of numerical examples to be performed within the open source C++ finite volume library OpenFOAM.

## Location

All lectures will be delivered in one of SISSA classrooms and streamed online using the Zoom platform. A link with the lecture will be provided to the students at the end of every lecture.

The following Zoom link will be used for the lectures:

https://sissa-it.zoom.us/j/84449538589?pwd=dVNjVkRNcWdVSG1YQUxqTFhFVWl1Zz09

## Registration

Students willing to follow are requested to compile [this form](https://docs.google.com/forms/d/e/1FAIpQLSdafSBTFcd7IyT5SA-CY951tVVsLQXry98DuwTz-n1FjmRJrQ/viewform)


## Frontal Lectures

##### Module 0
- Introduction to Finite Volume discretization

##### Module 1: Ocean and Atmospheric Flows
- Navier-Stokes equations in stream function-vorticity formulation
- Quasi Geostrophic equations
- Compressible Euler equations for nearly hydrostatic flows

##### Module 2: Cardiovascular Flows
- Multiscale modelling for the simulation of the blood flows in idealized geometries
- Applications to patient-specific configurations

##### Module 3: Industrial applications
- Multiphase and conjiugate heat transfer modelling for refrigeration systems
- Fluid-solid modeling for pharmaceutical applications

## Exam

For the examination, you are requested to complete two practical exercises and to do an oral examination. 

## About OpenFOAM installation

Before using the docker container you need to install docker into your system. 

[Here](https://docs.docker.com/get-docker/) the instructions.

```
git clone https://github.com/mgirfogl/MACFD2023.git
```

Then:

```
cd MACFD2023
chmod +x openfoam-docker
```

After that you can activate docker using the OpenFOAM folder.

```
./openfoam-docker -dir=OpenFOAM
```


## References and Text Books:


## Material

This repository contains, assignements, workspaces, and other material for the course.

New material will be uploaded frequently.

## Acknowledgements

I would like to aknowledge [Dr. Giovanni Stabile](giovanni.stabile@uniurb.it) for his contribution to the preparation of the slides presented in the first lecture of this course as well as [Dr. Arash Hajisharifi](ahajisha@sissa.it) for helding a seminar during the last lecture.

**Please consider contributing pull requests to correct typos, or better document the material in this repository!**

## Licencing

The content of this repository is distributed with a Creative Common licence. See
the file LICENCE.md in this directory for more information.

