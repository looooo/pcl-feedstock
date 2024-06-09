About pcl-feedstock
===================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/pcl-feedstock/blob/main/LICENSE.txt)

Home: http://www.pointclouds.org

Package license: BSD-3-Clause

Summary: Point Cloud Library (PCL)

Development: https://github.com/pointcloudlibrary/pcl

Documentation: http://www.pointclouds.org

The Point Cloud Library (PCL) is a standalone, large scale, open project for 2D/3D image and point cloud processing.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5677&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pcl-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-pcl-green.svg)](https://anaconda.org/freecad/pcl) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/pcl.svg)](https://anaconda.org/freecad/pcl) | [![Conda Version](https://img.shields.io/conda/vn/freecad/pcl.svg)](https://anaconda.org/freecad/pcl) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/pcl.svg)](https://anaconda.org/freecad/pcl) |

Installing pcl
==============

Installing `pcl` from the `freecad/label/qt6` channel can be achieved by adding `freecad/label/qt6` to your channels with:

```
conda config --add channels freecad/label/qt6
conda config --set channel_priority strict
```

Once the `freecad/label/qt6` channel has been enabled, `pcl` can be installed with `conda`:

```
conda install pcl
```

or with `mamba`:

```
mamba install pcl
```

It is possible to list all of the versions of `pcl` available on your platform with `conda`:

```
conda search pcl --channel freecad/label/qt6
```

or with `mamba`:

```
mamba search pcl --channel freecad/label/qt6
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search pcl --channel freecad/label/qt6

# List packages depending on `pcl`:
mamba repoquery whoneeds pcl --channel freecad/label/qt6

# List dependencies of `pcl`:
mamba repoquery depends pcl --channel freecad/label/qt6
```




Updating pcl-feedstock
======================

If you would like to improve the pcl recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/pcl-feedstock are
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

* [@Tobias-Fischer](https://github.com/Tobias-Fischer/)
* [@chambbj](https://github.com/chambbj/)
* [@hobu](https://github.com/hobu/)

