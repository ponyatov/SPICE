# Qucs (`qucs-spice`)

- https://snapcraft.io/install/qucs-spice/debian
- http://qucs.sourceforge.net/install.html

The package contains [[ASCO]], [[FreeHDL]] and [[ADMS]].

[[Icarus Verilog]] is used for digital [[Verilog-HDL]] simulation

## on Debian
- [official down](https://packages.qa.debian.org/q/qucs.html)
- **https://download.opensuse.org/repositories/home:/ra3xdh/**

![[SPICE/qucs/snap]]

## Qucs-S: Qucs with SPICE

https://ra3xdh.github.io/

Qucs-S is a spin-off of the [Qucs](http://qucs.github.io/) cross-platform circuit simulator. "S" letter indicates SPICE. The purpose of the Qucs-S subproject is to use free SPICE circuit simulation kernels with the Qucs GUI. It merges the power of SPICE and the simplicity of the Qucs GUI. Qucs intentionally uses its own SPICE incompatible simulation kernel Qucsator. It has advanced RF and AC domain simulation features, but most of the existing industrial SPICE models are incompatible with it. Qucs-S is not a simulator by itself, but it requires to use a simulation backend with it. The schematic document format of Qucs and Qucs-S are fully compatible. Qucs-S allows to use the following simulation kernels with it:

-   [Ngspice](http://ngspice.org/) is recommended to use. Ngspice is powerful mixed-level/mixed-signal circuit simulator. The most of industrial SPICE models are compatible with Ngspice. It has an excellent performance for time-domain simulation of switching circuits and powerful postprocessor.
-   [XYCE](https://xyce.sandia.gov/) is a new SPICE-compatible circuit simulator written by Sandia from the scratch. It supports basic SPICE simulation types and has an advanced RF simulation features such as Harmonic balance simulation.
-   [SpiceOpus](http://spiceopus.si/) is developed by the Faculty of Electrical Engineering of the Ljubljana University. It based on the SPICE-3f5 code
-   Qucsator as backward compatible


## Publications

Qucs-S is not a simple circuit simulator, but also a research software. Please cite our articles, if you are using Qucs-S in your research.

1.  Brinson, M. E., and Kuznetsov, V. (2016) A new approach to compact semiconductor device modelling with Qucs Verilog-A analogue module synthesis. Int. J. Numer. Model., 29: 1070-1088. ([BibTeX](https://ra3xdh.github.io/ijnm.bib))
2.  D. Tomaszewski, G. Głuszko, M. Brinson, V. Kuznetsov and W. Grabinski, "FOSS as an efficient tool for extraction of MOSFET compact model parameters," 2016 MIXDES - 23rd International Conference Mixed Design of Integrated Circuits and Systems, Lodz, 2016, pp. 68-73. ([BibTeX](https://ra3xdh.github.io/foss_mixdes.bib))
3.  M. Brinson and V. Kuznetsov, "Qucs-0.0.19S: A new open-source circuit simulator and its application for hardware design," 2016 International Siberian Conference on Control and Communications (SIBCON), Moscow, 2016, pp. 1-5. ([BibTeX](https://ra3xdh.github.io/qucs_sibcon.bib))
4.  M. Brinson and V. Kuznetsov, "Improvements in Qucs-S equation-defined modelling of semiconductor devices and IC's," 2017 MIXDES - 24th International Conference "Mixed Design of Integrated Circuits and Systems, Bydgoszcz, 2017, pp. 137-142. ([BibTeX](https://ra3xdh.github.io/qucs_s_mixdes.bib))
5.  M. Brinson and V. Kuznetsov, "Extended behavioural device modelling and circuit simulation with Qucs-S" International Journal of Electronics, 2017, pp.1 - 14 ([BibTeX](https://ra3xdh.github.io/qucs_ije.bib))

## setup

![[qucs00.png]]
![[qucs01.png]]
![[qucs02.png]]
