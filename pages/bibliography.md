---
description: Papers, posters, talks, etc.
---

# Bibliography

[ORCID](https://orcid.org/0009-0002-0982-8149)

## [ARBFN: Arbitrary Externally-Computed Closed-Loop Force Fixes in LAMMPS](https://github.com/jorbDehmel/lammps_ARBFN)

Spring 2025, paper in preparation for journal submission

**Jordan Dehmel (CMU)**, Jarrod Schiffbauer (CMU)

Abstract:

> The molecular dynamics simulation software LAMMPS
> (Large-scale Atomic/Molecular Massively Parallel Simulator)
> provides a scripting language for the easy implementation of
> experiments: However, it is not all-encompassing. There are
> many situations in which LAMMPS alone is not sufficient and
> some external computation must be used, for example, including
> quantum effects [Kohlmeyer, Ippolito, Cavazzoni, 2014] and
> machine learning control [Rohskopf et. al., 2023] of a
> simulation. Such situations provide some custom interface for
> a specific program to apply forces on the simulated particles.
> This project outlines the development of a generic protocol
> for this process. Specifically, we introduce an
> externally-controlled arbitrary atomic forcing fix within the
> existing MPI (Message Passing Interface) LAMMPS framework
> [OpenMPI, 2003] [Thompson et. al., 2024]. This involves an
> arbitrary-language controller program being instantiated
> alongside LAMMPS in an MPI runtime, then communicating with
> all LAMMPS instances whenever the desired fix must be
> computed. The protocol communicates in JSON (JavaScript Object
> Notation) strings and assumes no controller linguistic
> properties beyond a valid MPI implementation.

## [Study and Investigation of behavior of Janus particles in different concentration KCl electrolytes mixed with glycerol](https://meetings.aps.org/Meeting/DFD24/Session/S01.51)

November 2024, Poster for the 2024 APS 77th Annual Meeting of
the Division of Fluid Dynamics

Sandeep Ramteke (FIU), **Jordan Dehmel (presenter, CMU)**,
Alicia Boymelgreen (FIU), Jarrod Schiffbauer (CMU)

## Vulnerability and Data Flow Analysis on Arbitrary Languages with Code Property Graphs and Taint Traversals

Summer 2024, paper in-progress

**Jordan Dehmel (CMU)** and Warren MacEvoy (CMU)

Abstract:

> When assessing the security of code, it is paramount to ensure
> that security-privileged routines do not disclose secret
> information to would-be attackers. Similarly, when interacting
> with important and abstract APIs like databases, it must be
> ensured that no unverified user input be allowed direct access
> (EG SQL injection attacks). These problems both involve
> tracking the contributors and dependents of variables at
> debugging time, a common task in analysis and linting. This
> paper examines the use of Code Property Graphs (CPGs)
> [Yamaguchi, Golde, Arp and Rieck, 2014] and taint-style
> vulnerability scanning [Sabelfeld and Myers, 2003] in such a
> context. CPGs are dense and expressive representations of
> program syntax, dependency, and control flow often used in
> linting. Taint-style vulnerability scanning, on the other
> hand, tracks possible vulnerabilities along variable
> modifications and control flow alterations such that sensitive
> data does not flow beyond its desired scope. This paper
> describes a language-agnostic algorithm for the construction
> of CPGs with embedded information-flow security measures and
> details the development of a VSCode extension utilizing them.

## Colloidal Janus Particles Under Applied Electric Fields in Microgravity and comparison to Similar Results via Terrestrial Density Matching (Working Title)

Fall 2024, paper, in journal review

Sandeep Ramteke (FIU), **Jordan Dehmel (CMU)**, Alicia
Boymelgreen (FIU),  Jarrod Schiffbauer (CMU)

Resulted in the launching of extraterrestrial ISS experiments on
the effects of microgravity on colloidal active matter in August
2024, as well as novel experiments involving density matching on
Earth for the avoidance of gravity-related error.

## Colloidal Active Matter Under Applied Electric Fields

Fall 2024, Poster for the 2024 RMACC HPC Symposium Student
Poster Competition.

**Jordan Dehmel (CMU)**, Sandeep Ramteke (FIU), Jarrod
Schiffbauer (CMU), Alicia Boymelgreen (FIU)

## Individual and Collective Motion in Colloidal Active Matter Under Applied Electric Fields: Experimental and Computational Perspectives

Fall 2024, Presentation for the 2024 Colorado Mesa University
Student Showcase

**Jordan Dehmel (CMU)**, Sandeep Ramteke (FIU), Jarrod
Schiffbauer (CMU), Alicia Boymelgreen (FIU)

## [What time is it: How do computers know what time it is?](https://github.com/jorbDehmel/masc-projects)

August 2023, Children’s exhibit for the Eureka! McConnell
Science Museum

**Jordan Dehmel (CMU)**
