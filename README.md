# Conan: Distributed Proofs of Compliance for Anonymous Data Collection (CCS '24)

This is a prototype implementation of the Conan protocol. See our paper: https://eprint.iacr.org/2023/1900

**Warning**: The code is not audited and is not intended for any serious commercial or real-world use case. Please use it only for educational purposes.

### Prerequisite:
1. Install Go(https://go.dev/doc/install).

### Running Experiments:

First, `go mod tidy` to set up the dependencies.

1. `go run dp_sum/dp_sum.go`
2. `go run vec_sum/vec_sum.go`
3. `go run vote/vote.go`
4. `go run aml/aml.go`
5. `go run blame/blame.go`

Each line will generate a CSV file on the main directory for the experiment results.

### Contact

Mingxun Zhou (mingxunz@andrew.cmu.edu)

### Citation

@inproceedings{conan,
  title={Conan: Distributed Proofs of Compliance for Anonymous Data Collection},
  author={Zhou, Mingxun and Fanti, Giulia and Shi, Elaine},
  booktitle={CCS},
  year={2024}
}


