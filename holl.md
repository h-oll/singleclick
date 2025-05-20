# Single Click Protocol     :pbl:

## Notes


### [2025-05-20 Tue]  Initial idea     :export:

1.  Context

    -   Single click protocol has better performance regarding the transmission rate for creating $\ket{+_{\theta}}$ states.
    -   There is currently no (dis)-proof of security for this protocol regarding the possibility ot use it as the transmission step for RSP.
    -   The security of the single click protocol also has implications for twin field QKD because of the proximity with the states being sent by both protocols &#x2013; yet the objectives remain widely different and the context as well, making that topic a separate concern.

2.  Objetives

    -   Explore the security of the single click protocol for RSP purposes
    -   Understand and possibly improve the security proofs of twin field QKD

3.  Propositions

    -   Description of the single click protocol
    -   Description of the twin field QKD protocol
    -   Aggregation of previous arguments brought against the security of the protocol for RSP
    -   Analysis of the QKD security proof
    -   Definition of a concrete attack on the protocol for RSP
        1.  Coming back to WCP
            1.  split the beam between less than 1 photon Fock subspace and more than two photons
            2.  perform a measurement of the phase when we are in the more than 2 photons.
        2.  Crafting a gentle measurement, where the "gentle part" is only on a given subspace
        3.  Trying to bin two pulses together and see how much more efficient things can be / or can we perform some de Finetti approximation
