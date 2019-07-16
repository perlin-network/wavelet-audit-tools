# Wavelet Audit Tools

This repository contains all fuzzing and network simulation code written and used by the Dag-One team to audit Wavelet. The full audit report for Wavelet may be found [here](report.pdf).

The fuzzing code, in the `fuzz/` directory, was built using [go-fuzz](https://github.com/dvyukov/go-fuzz).

The network simulation code, in the `netsim/` directory, was used to simulate
various network configurations on a single machine to test how Wavelet
responded to numerous modes.
