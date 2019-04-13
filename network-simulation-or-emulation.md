# Network simulation or emulation?
**Source**: https://www.networkworld.com/article/3227076/network-simulation-or-emulation.html

## Original abstract
> In regard to network testing, the terms emulation and simulation are often used interchangeably. In most cases, either term will generally get the point across, but there’s a big difference between a network emulator and network simulator, both practically and semantically.

## Summary

Network engineers have the responsibility of not misconfiguring real infrastructures, due to the high cost of that happening. Every step of a critical operation must be systematically tested.

The terms *emulation* and *simulation* are often used interchangeably, but there is a big difference between both words.

> A simulator can perform tasks in *abstract* to *demonstrate* the *behavior* of a network and its components, while an emulator can *copy* the behavior of a network to *functionally replace* it.

### Simulators

Simulators are based on the mathematical models (in this case of computer networks), they offer an abstraction completely virtual.

Simulators like ns-3 use *discrete event simulation* which treats everything that happens in the network as an *event* that is *queued* and *processed* like a data flow. Performance can be *hypothesized*.

### Emulators

Network emulators can accurately reproduce a client/server network connection without the need for a router, as long as a for the emulator way to "run" between the rest of the network nodes is provided.

## Useful stuff

The quoted, very succinct distinction between emulator and simulator.
