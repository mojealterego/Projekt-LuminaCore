# LuminaCore — Roadmap

Status legend: `[ ]` not completed; `[x]` evidenced as completed. Milestone completion requires linked artifacts, test results and review.

## Phase 0 — Research foundations
- [ ] Define use cases, system requirements, SWaP constraints and baseline digital accelerators.
- [ ] Review primary literature, foundry PDK access, material compatibility, and IP landscape.
- [ ] Define measurement methodology: wall-plug energy per inference, end-to-end latency, throughput, accuracy and thermal stability.
- [ ] Establish reproducible simulation, CI, versioned datasets and traceable evidence.

## Phase 1 — Optical device models (proposal: months 1–3)
- [ ] Develop validated models of MZI, MRR, waveguide losses and phase errors.
- [ ] Model WDM crosstalk, source/detector noise and calibration.
- [ ] Characterize VO2 activation hypotheses including threshold, hysteresis, switching energy and lifetime.
- [ ] Evaluate SiN/BTO/VO2 integration and fabrication feasibility with foundry partners.
- [ ] Gate: independently reproducible simulation and manufacturable design review before tape-out.

## Phase 2 — Compiler and SDK (proposal: months 4–8)
- [ ] Define optical intermediate representation, operator coverage and calibration constraints.
- [ ] Import supported PyTorch models and map linear layers to constrained MZI/MRR configurations.
- [ ] Provide quantization/noise-aware evaluation and digital fallback for unsupported operations.
- [ ] Gate: regression suite against numerical reference with declared tolerances.

## Phase 3 — PIC characterization (proposal: months 9–14)
- [ ] Complete tape-out only after design rule checks, foundry signoff and budget approval.
- [ ] Build safe laser test setup, optical instrumentation and FPGA control interface.
- [ ] Measure optical transfer, loss, crosstalk, switching behavior and environmental sensitivity.
- [ ] Gate: archived raw measurements and independent replication.

## Phase 4 — IP and transfer (proposal: months 15–18)
- [ ] Perform prior-art and freedom-to-operate review with qualified counsel.
- [ ] Decide on patents, publications and trade secrets before disclosure.

## Phase 5 — Demonstration (proposal: months 19–24)
- [ ] Demonstrate edge inference on a representative robotics control workload.
- [ ] Benchmark against realistic digital baselines at matched accuracy and system boundary.
- [ ] Prepare evidence-based investor and grant materials.

## Indicative budget from application (not awarded)
| Period | USD |
|---|---:|
| Months 1–3 | 60,000 |
| Months 4–8 | 40,000 |
| Months 9–14 | 90,000 |
| Months 15–18 | 30,000 |
| Months 19–24 | 30,000 |
| **Total** | **250,000** |

This roadmap will be updated after each verified milestone. Planned achievements are not marked completed.
