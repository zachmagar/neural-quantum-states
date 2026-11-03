# Neural Quantum States

A PyTorch research project investigating whether symmetry-aware transformer wavefunctions are able to approximate quantum ground states more efficiently than conventional neural-network architectures.

## Research question

Can a symmetry-aware transformer achieve lower ground-state energy error than a conventional neural wavefunction under a fixed computational budget?

## Planned implementation

- Exact ground-state solver for small quantum spin systems
- MLP neural wavefunction baseline
- Symmetry-aware MLP and transformer architectures
- Variational energy optimization
- Reproducible architecture benchmarks

## Installation

Requires Python 3.11 or 3.12.

Create and activate a virtual environment, then run:

```bash
python -m pip install -e ".[dev]"
```

## Status

**In development**

## License

MIT