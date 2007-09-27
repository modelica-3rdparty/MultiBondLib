# MultiBondLib
Free library to model physical systems with multi-bond graphs.

## Library description

Multi-bond graphs are vector-bond graphs designed primarily for modeling 2D and 3D mechanical systems.

`MultiBondLib` implements the multi-bond graph methodology, and offers an alternative implementation to the multi-body systems library by Martin Otter. Whereas Otter's multi-body component models (such as a revolute joint) are implemented internally by (matrix/vector) equations, the implementation offered here decomposes multi-body component models graphically into wrapped multi-bond graphs. This makes the new library more easily maintainable. The run-time efficiency of both libraries for the simulation of 3D mechanical systems is identical.

`MultiBondLib` offers also a separate 2D mechanical library as well as an enhanced 3D mechanical library for modeling hard impacts between bodies and also gravitational pools.

The 3D mechanical connectors of `MultiBondLib` are not compatible with the corresponding connectors of the Modelica Standard Library. Consequently, the component models of the two libraries cannot be mixed.

*The library won in 2006 the first price of the Modelica Association for a free Modelica library.*

### Dependencies
`MultiBondLib` represents an extension to [BondLib](https://github.com/modelica-3rdparty/BondLib) in that it offers interfaces to the 1D mechanical (translational and rotational) libraries of [BondLib](https://github.com/modelica-3rdparty/BondLib). Thus, if you plan on using `MultiBondLib`, you should download [BondLib](https://github.com/modelica-3rdparty/BondLib) as well.


## Current release

Download [MultiBondLib v1.3 (2007-09-29)](../../archive/v1.3.zip)

#### Release notes

* [Version v1.3 (2007-09-29)](../../archive/v1.3.zip)
  * adds actuated prismatic and revolute joints

## License

This Modelica package is free software and the use is completely at your own risk;
it can be redistributed and/or modified under the terms of the [Modelica License 2](https://modelica.org/licenses/ModelicaLicense2).

## Development and contribution
`MultiBondLib` was realized in 2005/2006 by [Dirk Zimmer](mailto:Dirk.Zimmer@dlr.de) as part of his MS Thesis research.
