# QoS-P4bSub Artifacts (NOMS 2026)

This repository contains the source code and experimental scripts for our NOMS 2026 submission on Delay-Sensitive In-Network QoS Management for Publish/Subscribe Communications.


## 1. Prerequisites
- **Hardware:** Intel Tofino ASIC (SDE v9.13.4)
- **Software:** Python 3.8+, PTF Framework


## Reproduction Workflow

# 1. Build P4 Pipeline
```
./scripts/build.sh
```

# 2. Run Test Suite
```
./scripts/run_tofino_model.sh   # Terminal 1
./scripts/run_app.sh            # Terminal 2
./scripts/run_ptf_tests.sh      # Terminal 3
```

---

## Citation

If you use `QoS-P4bSub` in your research, please cite **Chapter 3** of the doctoral dissertation:

```bibtex
@phdthesis{boughzala2026accelerating,
  author  = {Bochra Boughzala},
  title   = {Accelerating Real-Time Data-Analytics with In-Network Computing: Programmable Packet Processors for Enhancing the Efficiency of Distributed Stream Processing},
  school  = {University of Groningen},
  year    = {2026},
  note    = {Chapter 3: Stabilizing QoS Guarantees in Delay-Sensitive Pub/Sub Communications}
}
```

You can also cite the accompanying conference paper:

```bibtex
@inproceedings{boughzala2026qos,
  author    = {Boughzala, B. and Koldehofe, B.},
  title     = {Delay-Sensitive In-Network QoS Management for Publish/Subscribe Communications},
  booktitle = {IEEE/IFIP Network Operations and Management Symposium (NOMS 2026)},
  year      = {2026}
}
```
