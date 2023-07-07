# WhyBSML

## Overview

The [OCaml](https://ocaml.org) language is a versatile programming language that combines functional, imperative and object-oriented paradigms. [BSML](https://bsml-lang.github.io) (Bulk Synchronous Parallel ML) is an OCaml-based library that embodies the principles of the BSP ([Bulk Synchronous Parallel](https://www.youtube.com/watch?v=jDlapnjlk-o)) model. It provides a range of constants and functions to facilitate BSP programming. 

The BSP machine, viewed as a homogeneous distributed memory system with a point-to-point communication network and a global synchronization unit, serves as the underlying architecture for BSML. BSP programs, composed of consecutive super-steps, run on this kind of machine. The execution of each super-step follows a distinct pattern, starting with the computation phase where each processor-memory pair performs local computations using data available locally. This phase is followed by the communication phase, during which processors can request and exchange data with other processors. Finally, the synchronization phase concludes the super-step, synchronizing all processors globally.
With its collection of four expressive functions and some constants, BSML allows developers to write BSP programs. 

WhyBSML is a set of WhyML modules (the langage of [Why3](https://why3.lri.fr)) that formalize the BSML primitives and that use this formalization to implement and verify parallel functions. Compilable OCaml and BSML code can be extracted from WhyBSML and run on parallel machines.

## Software

- [WhyBSML](https://github.io/whybsml/whybsml)

## Publications


## Theses 

- Olivia Proust, Vérification déductive de programmes fonctionnels parallèles extensibles, BSc Thesis, Université d'Orléans, June 2023

