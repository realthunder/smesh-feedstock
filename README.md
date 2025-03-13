About smesh-feedstock
=====================

Feedstock license: [BSD-3-Clause](https://github.com/realthunder/smesh-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/LaughlinResearch/SMESH

Package license: LGPL-2.1-or-later

Summary: A complete MESH framework based on the OCCT library.

Standalone version of the meshing library from the Salome Platform.

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-smesh-green.svg)](https://anaconda.org/realthunder/smesh) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/smesh.svg)](https://anaconda.org/realthunder/smesh) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/smesh.svg)](https://anaconda.org/realthunder/smesh) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/smesh.svg)](https://anaconda.org/realthunder/smesh) |

Installing smesh
================

Installing `smesh` from the `realthunder` channel can be achieved by adding `realthunder` to your channels with:

```
conda config --add channels realthunder
conda config --set channel_priority strict
```

Once the `realthunder` channel has been enabled, `smesh` can be installed with `conda`:

```
conda install smesh
```

or with `mamba`:

```
mamba install smesh
```

It is possible to list all of the versions of `smesh` available on your platform with `conda`:

```
conda search smesh --channel realthunder
```

or with `mamba`:

```
mamba search smesh --channel realthunder
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search smesh --channel realthunder

# List packages depending on `smesh`:
mamba repoquery whoneeds smesh --channel realthunder

# List dependencies of `smesh`:
mamba repoquery depends smesh --channel realthunder
```




Updating smesh-feedstock
========================

If you would like to improve the smesh recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`realthunder` channel, whereupon the built conda packages will be available for
everybody to install and use from the `realthunder` channel.
Note that all branches in the realthunder/smesh-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@realthunder](https://github.com/realthunder/)

