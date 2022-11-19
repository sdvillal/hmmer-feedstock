About hmmer
===========

Home: http://hmmer.org/

Package license: BSD

Feedstock license: [BSD-3-Clause](https://github.com/sdvillal/hmmer-feedstock/blob/master/LICENSE.txt)

Summary: Biosequence analysis using profile hidden Markov models

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/hmmer-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/hmmer-feedstock?branchName=master&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/hmmer-feedstock?branchName=master&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/hmmer-feedstock?branchName=master&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/hmmer-feedstock?branchName=master&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-hmmer-green.svg)](https://anaconda.org/sdvillal/hmmer) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/hmmer.svg)](https://anaconda.org/sdvillal/hmmer) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/hmmer.svg)](https://anaconda.org/sdvillal/hmmer) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/hmmer.svg)](https://anaconda.org/sdvillal/hmmer) |

Installing hmmer
================

Installing `hmmer` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
conda config --set channel_priority strict
```

Once the `sdvillal` channel has been enabled, `hmmer` can be installed with `conda`:

```
conda install hmmer
```

or with `mamba`:

```
mamba install hmmer
```

It is possible to list all of the versions of `hmmer` available on your platform with `conda`:

```
conda search hmmer --channel sdvillal
```

or with `mamba`:

```
mamba search hmmer --channel sdvillal
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search hmmer --channel sdvillal

# List packages depending on `hmmer`:
mamba repoquery whoneeds hmmer --channel sdvillal

# List dependencies of `hmmer`:
mamba repoquery depends hmmer --channel sdvillal
```




Updating hmmer-feedstock
========================

If you would like to improve the hmmer recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/hmmer-feedstock are
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


