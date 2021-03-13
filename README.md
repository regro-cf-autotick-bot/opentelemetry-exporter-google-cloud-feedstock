About opentelemetry-exporter-google-cloud
=========================================

Home: https://github.com/GoogleCloudPlatform/opentelemetry-operations-python/tree/master/opentelemetry-exporter-google-cloud

Package license: Apache-2.0

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/opentelemetry-exporter-google-cloud-feedstock/blob/master/LICENSE.txt)

Summary: OpenTelemetry Google Cloud Integration

Documentation: https://google-cloud-opentelemetry.readthedocs.io/en/latest/

Provides OpenTelemetry Python exporters for Google Cloud Platform.

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=11833&branchName=master">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/opentelemetry-exporter-google-cloud-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-opentelemetry--exporter--google--cloud-green.svg)](https://anaconda.org/conda-forge/opentelemetry-exporter-google-cloud) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/opentelemetry-exporter-google-cloud.svg)](https://anaconda.org/conda-forge/opentelemetry-exporter-google-cloud) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/opentelemetry-exporter-google-cloud.svg)](https://anaconda.org/conda-forge/opentelemetry-exporter-google-cloud) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/opentelemetry-exporter-google-cloud.svg)](https://anaconda.org/conda-forge/opentelemetry-exporter-google-cloud) |

Installing opentelemetry-exporter-google-cloud
==============================================

Installing `opentelemetry-exporter-google-cloud` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `opentelemetry-exporter-google-cloud` can be installed with:

```
conda install opentelemetry-exporter-google-cloud
```

It is possible to list all of the versions of `opentelemetry-exporter-google-cloud` available on your platform with:

```
conda search opentelemetry-exporter-google-cloud --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating opentelemetry-exporter-google-cloud-feedstock
======================================================

If you would like to improve the opentelemetry-exporter-google-cloud recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/opentelemetry-exporter-google-cloud-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@twoodwark](https://github.com/twoodwark/)
