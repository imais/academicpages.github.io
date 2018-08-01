---
title: "Projects"
permalink: /projects/
author_profile: true
---

## QoS-Aware Elastic Virtual Machine Scheduling
* Explored cloud-based elastic virtual machine scheduling for
  batch, micro-batch, and stream processing models.
* Saved up to 49% cost compared to a conventional static scheduling technique.
* Developed a [web-dashboard](https://github.com/imais/stream-dashboard) to monitor offset lags for Kafka for stream processing:

  <video controls width="560" height="315" src="../files/videos/kafka-dashboard.webm" poster="../files/videos/kafka-dashboard.png"> </video>


## PILOTS
* Researched a new domain-specific programming language [PILOTS](http://wcl.cs.rpi.edu/pilots/) for spatio-temporal data streaming application to facilitate the development of smarter flight systems.
* Development of PILOTS was inspired by the Air France 447 accident which original cause of the accident was airspeed sensor failures. PILOTS tries to detect data errors by cross-checking multiple data streams and fix them when possible.
* Local news exposures: [Troy Record](http://www.troyrecord.com/general-news/20140406/rpi-research-group-working-on-a-facet-of-airline-problems-currently-in-news), [Albany Times Union](https://m.timesunion.com/default/article/Software-developed-to-detect-fix-data-errors-5377823.php).
* Demo video of a PILOTS program detecting and correcting the airspeed sensor failure occurred in the Air France 447 accident:

  <video controls width="560" height="315" src="../files/videos/pilots-af447.mov" poster="../files/videos/pilots-af447.jpg"> </video>

## Enhancements to SALSA
* Added experimental [new features](../files/salsa/salsa-new-features.pdf) for the [SALSA](http://wcl.cs.rpi.edu/salsa/) programming language:
  - "netif" option support for theaters to specify which network interface to use.
  - Android support
    * Modified SALSA source code (based on v1.1.5): [salsa1.1.5.tgz](../files/salsa/salsa1.1.5.tgz).
    * SALSA theater code for Android: [AndroidTheaterService.java](../files/salsa/AndroidTheaterService.java), [MainActivity.java](../files/salsa/MainActivity.java).
    * Migration test code: [Migrate.salsa](../files/salsa/Migrate.salsa).
  - "extip" option support to enable migration to/from virtual machines on Amazon EC2.
  
## C-Snap with 3D
* Integrated a [3D-system](http://csdt-imais.blogspot.com/) to the [C-Snap](https://github.com/CSnap/CSnap) visual programming environment using *three.js*.
* This was a summer research project supervised by Professor [Eglash](http://homepages.rpi.edu/~eglash/eglash.htm) and Professor [Moorthy](http://www.cs.rpi.edu/~moorthy/).

  

  
