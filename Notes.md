## Notes

Fuzz: Tries to break properties by throwing random data at your system

Formal Verification: Tries to break properties using mathematical proofs

* pass the mathematical proof into a solver, where the solver will eithr return true or false 
|_ SMT Solver or SAT Solver ( --> SMT Lib langauge --> Z3 tool )

* Process:

-> 1. Explore paths
-> 2. Convert paths to a set of booleans
-> 3. See if paths are reachable

* Command

```bash
solc --model-checker-engine chc --model-checker-targets <what you are checking> <FileName>.sol
```

Resources:

https://blog.sigmaprime.io/solidity-security.html

https://damvulnerabledefi.xyz

https://ethernaut.openzeppelin.com

https://solodit.xyz