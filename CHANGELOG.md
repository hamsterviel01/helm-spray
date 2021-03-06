# Release Notes

## Version 4.0.1 - 06/18/2020
* Fixed [`#55`](https://github.com/ThalesGroup/helm-spray/issues/55)

## Version 4.0.0 - 06/11/2020
* Bump to helm v3 (this version is NOT compatible with helm v2)

## Version 3.4.6 - 03/20/2020
* Plugin installation via helm plugin install is now possible

## Version 3.4.5 - 10/08/2019
* Bugfix issues #39, #40 and #41 [`#42`](https://github.com/gemalto/helm-spray/pull/42) (Patrice Amiel)

## Version 3.4.4 - 09/04/2019
* Support other Deployment/StatefulSet versions for the 'waiting for' phase [`#30`](https://github.com/gemalto/helm-spray/pull/30) (Patrice Amiel) 
* Support of Helm Tags [`#35`](https://github.com/gemalto/helm-spray/pull/35) (Patrice Amiel) 

## Version 3.4.3 - 07/15/2019
* Support of new flags (--exclude, --set-file, --set-string) + bugfix #! .File.Get clause [`#28`](https://github.com/gemalto/helm-spray/pull/28) (Patrice Amiel) 

## Version 3.4.2 - 05/23/2019
* Bugfix regexp for '.File.Get' for windows [`3a2a527`](https://github.com/gemalto/helm-spray/commit/3a2a5279f078391e7d8b421d7e3aa69f425ebcac) (Patrice Amiel)

## Version 3.4.1 - 05/23/2019
* Bump to go 1.11 [`ea90f7a`](https://github.com/gemalto/helm-spray/commit/ea90f7a686065dec9a9308bce4ebc3ac03a8dd4a) (Christophe Vila)

## Version 3.4.0 - 05/22/2019
* Support of "Multiple values files in the umbrella chart" [`#20`](https://github.com/gemalto/helm-spray/pull/20) [`#21`](https://github.com/gemalto/helm-spray/pull/21) (Patrice Amiel)

## Version 3.3.0 - 03/25/2019
* Enhance "wait liveness and readiness" and create capability to prefix releases names [`#16`](https://github.com/gemalto/helm-spray/pull/16) (Patrice Amiel)

## Version 3.2.1 - 02/14/2019
* Bugfixes on "waiting for Liveness and Readiness" step [`#14`](https://github.com/gemalto/helm-spray/pull/14) (Patrice Amiel)

## Version 3.2.0 - 02/01/2019
* Fix plugin.yaml executable name according to OS [`#5`](https://github.com/gemalto/helm-spray/pull/5) (Christophe Vila)
* Support of alias and of the '--force' option [`#3`](https://github.com/gemalto/helm-spray/pull/3) (Patrice Amiel)

## Version 3.1.0 - 01/27/2019
* Adding support of several -f clauses
* Adding debug option 
* Supporting HELM_DEBUG envar to get the debug mode as helm is not forwarding the --debug option

## Version 3.0.0 - 11/10/2018
* First delivery on Github.
