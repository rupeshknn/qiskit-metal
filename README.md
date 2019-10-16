# Qiskit Metal
### Quantum VLSI and Sims

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/zlatko-minev/pyEPR)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/zlatko-minev/pyEPR)

# Docs and how to use

Todo.

# Installation notes

For development, the best way is to fork the repository. Then install the following required packages. Certain packages are only required if you require a particulat plugin. For example, if one does not require to export to gds, one does not need to install pygds.

#### Core packages
```
conda install shapely
```

Install pyEPR(https://github.com/zlatko-minev/pyEPR)

#### Plugin: Export yo GDS for mask design
To use the GDS export plugin, please install `gdspy`. This will require you to first install Microsoft Visual C++ Build Tools, as a C++ compiler for speed is needed. This can be done with
```
pip install gdspy
```
If you do not already have the compiler, and get `error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": https://visualstudio.microsoft.com/downloads/`, please download the build tools from the site. You can find it under `Tools for Visual Studio` entitled `Build Tools for Visual Studio 20xx`. Note, you do not need to intsll the Windows SDK.


Additional packages
**Energy Participation Ratio**
  * Fully automated, eigen-analysis to calculate both the Hamiltonian and dissipative parameters of a distributed circuit, based on the fraction of energy stored in the non-linear/dissipative element in a given mode of the circuit

## Authors and Citation

Qiskit Metal is the work of [many people](https://github.com/Qiskit/qiskit-terra/graphs/contributors) who contribute to the project at different levels. Metal was concieved of and developed by Zlatko Minev at IBM, then co-led with Thomas McConkey. If you use Qiskit, please cite as per the included [BibTeX file](TODO).For icon attributions, see (\qiskit_metal\_gui\_imgs\icon_attributions.txt)


## License

[Apache License 2.0](LICENSE.txt)