About libtiledb-sql-py-feedstock
================================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/libtiledb-sql-py-feedstock/blob/main/LICENSE.txt)

Home: https://tiledb.com

Package license: GPL-2.0-only

Summary: libtiledb-sql-py is a Embedded Python SQL interface for TileDB arrays using the MyTile storage engine

Development: https://github.com/TileDB-Inc/TileDB-SQL-Py

Documentation: https://docs.tiledb.com/developer/api-usage/embedded-sql

libtiledb-sql-py is a fork of the mysqlclient-python which builds against libtiledb-sql to provide embedded sql querying of TileDB arrays.\n

Docs: https://docs.tiledb.com/developer/api-usage/embedded-sql

Source: https://github.com/TileDB-Inc/TileDB-SQL-Py

Upstream source: https://github.com/PyMySQL/mysqlclient-python


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9072&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libtiledb-sql-py-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9072&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libtiledb-sql-py-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9072&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libtiledb-sql-py-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9072&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libtiledb-sql-py-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9072&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libtiledb-sql-py-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9072&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libtiledb-sql-py-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libtiledb--sql--py-green.svg)](https://anaconda.org/jdblischak/libtiledb-sql-py) | [![Conda Downloads](https://img.shields.io/conda/dn/jdblischak/libtiledb-sql-py.svg)](https://anaconda.org/jdblischak/libtiledb-sql-py) | [![Conda Version](https://img.shields.io/conda/vn/jdblischak/libtiledb-sql-py.svg)](https://anaconda.org/jdblischak/libtiledb-sql-py) | [![Conda Platforms](https://img.shields.io/conda/pn/jdblischak/libtiledb-sql-py.svg)](https://anaconda.org/jdblischak/libtiledb-sql-py) |

Installing libtiledb-sql-py
===========================

Installing `libtiledb-sql-py` from the `jdblischak/label/test` channel can be achieved by adding `jdblischak/label/test` to your channels with:

```
conda config --add channels jdblischak/label/test
conda config --set channel_priority strict
```

Once the `jdblischak/label/test` channel has been enabled, `libtiledb-sql-py` can be installed with `conda`:

```
conda install libtiledb-sql-py
```

or with `mamba`:

```
mamba install libtiledb-sql-py
```

It is possible to list all of the versions of `libtiledb-sql-py` available on your platform with `conda`:

```
conda search libtiledb-sql-py --channel jdblischak/label/test
```

or with `mamba`:

```
mamba search libtiledb-sql-py --channel jdblischak/label/test
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search libtiledb-sql-py --channel jdblischak/label/test

# List packages depending on `libtiledb-sql-py`:
mamba repoquery whoneeds libtiledb-sql-py --channel jdblischak/label/test

# List dependencies of `libtiledb-sql-py`:
mamba repoquery depends libtiledb-sql-py --channel jdblischak/label/test
```




Updating libtiledb-sql-py-feedstock
===================================

If you would like to improve the libtiledb-sql-py recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`jdblischak` channel, whereupon the built conda packages will be available for
everybody to install and use from the `jdblischak` channel.
Note that all branches in the conda-forge/libtiledb-sql-py-feedstock are
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

* [@DimitrisStaratzis](https://github.com/DimitrisStaratzis/)
* [@ihnorton](https://github.com/ihnorton/)
* [@shelnutt2](https://github.com/shelnutt2/)

