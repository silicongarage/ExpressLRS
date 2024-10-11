![Banner](https://github.com/ExpressLRS/ExpressLRS-Hardware/blob/master/img/banner.png?raw=true)

<center>


[![License](https://img.shields.io/github/license/ExpressLRS/ExpressLRS?style=flat-square)](https://github.com/ExpressLRS/ExpressLRS/blob/master/LICENSE)

</center>

## ExpressLRS RX with Use-Best-Antenna mode

This branch reverts Stuck-Antenna-Mode introduced in 3.4.x releases back to Use-Best-Antenna mode in 3.3.x and prior.
Stuck-Antenna-Mode results in a TX configured with dynamic power spending an excessive percentage of time at MAX power state. Stuck-Antenna-Mode also significantly increases telemetry dropouts, as the best oriented diversity receiver antenna is no longer automatically chosen based on optimal RSSI.

Experiment at your own risk.



