# Introduction

## Philosophy
Less is More: don't do anything unnecessary
Break the rules: compromise between concerns

Pipeline
Structure hazards: hardware single execution
* multi core, parallel
Data hazards: instruction dependence (e.g., write same data)
* permissive check,  CAS, register rename
Control hazards: flow control
* Speculation - crystal ball to tell the future (e.g., url prefetch)

Memory Cache
improve locality (temporal or spatial), reduce misses
* cold miss -- prefetch
* capacity miss -- replacement (LRU, MFU)
* conflict miss -- conflict in shared cache line