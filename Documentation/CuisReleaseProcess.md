# The Cuis Smalltalk Release Process

This document describes the Process to handle Stable Releases for Cuis. It is inspired by RedHat Linux. These Stable Releases are created in specific repositories in the [Cuis Organization](https://github.com/Cuis-Smalltalk). Alpha development is done at the [Rolling Release of Cuis](https://github.com/Cuis-Smalltalk/Cuis-Smalltalk-Dev).

The process described here produces two releases per year: One in May and another November. 

## TL;DR (Short version) 

Goal is to do release of Cuis 7.0 on date May 31st. 

On date March 31st (D - 2 months), new development in the main Cuis-Smalltalk-Dev repo is ended, to focus on getting ready for the creation of Cuis 7.0 "release candidate". This is the Beta phase, it lasts 1 month. 

On date April 30th (D - 1 month), we create a repo for Cuis 7.0 "release candidate", and focus on QA and final tweaks on this release specific repo. This phase also lasts 1 month. 

On date May 31st we do release of Cuis 7.0 on the repo created above. 

After release, any critical fixes are pushed to the Cuis 7.0 repo. 

## Detailed version